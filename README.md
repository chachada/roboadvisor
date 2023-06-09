# roboadvisor

----- 테이블 설명 ------
- binance_sheet : 재무제표
  - """
rcept_no : 접수번호(14자리)
reprt_code : 보고서 코드 (1분기보고서 : 11013 반기보고서 : 11012 3분기보고서 : 11014 사업보고서 : 11011)
bsns : 사업년도 
corp_code : 공시대상회사의 고유번호(8자리)
sj_div : 재무제표구분	(BS : 재무상태표 IS : 손익계산서 CIS : 포괄손익계산서 CF : 현금흐름표 SCE : 자본변동표)
sj_nm :	재무제표명	(ex) 재무상태표 또는 손익계산서 출력)
account_id : 계정ID	(XBRL 표준계정ID ※ 표준계정ID가 아닐경우 ""-표준계정코드 미사용-"" 표시)
account_nm : 계정명	(계정명칭 ex) 자본총계)
account_detail : 계정상세	(※ 자본변동표에만 출력 ex) 계정 상세명칭 예시 - 자본 [member]|지배기업 소유주지분 - 자본 [member]|지배기업 소유주지분|기타포괄손익누계액 [member])
thstrm_nm :	당기명	(ex) 제 13 기)
thstrm_amount :	당기금액	(9,999,999,999 ※ 분/반기 보고서이면서 (포괄)손익계산서 일 경우 [3개월] 금액)
thstrm_add_amount :	당기누적금액	(9,999,999,999)
frmtrm_nm :	전기명	(ex) 제 12 기말)
frmtrm_amount :	전기금액	(9,999,999,999)
frmtrm_q_nm	: 전기명(분/반기)	(ex) 제 18 기 반기)
frmtrm_q_amount : 전기금액(분/반기)	(9,999,999,999 ※ 분/반기 보고서이면서 (포괄)손익계산서 일 경우 [3개월] 금액)
frmtrm_add_amount :	전기누적금액	(9,999,999,999)
bfefrmtrm_nm : 전전기명	(ex) 제 11 기말(※ 사업보고서의 경우에만 출력))
bfefrmtrm_amount : 전전기금액	(9,999,999,999(※ 사업보고서의 경우에만 출력))
ord	: 계정과목 정렬순서	(계정과목 정렬순서)
currency : 통화 단위	(통화 단위)
"""
