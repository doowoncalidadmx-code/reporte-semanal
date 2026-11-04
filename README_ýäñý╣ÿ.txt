주간 리포트 (Reporte Semanal) – 설치·사용 방법

■ 바로 쓰기 (설치 없이)
  index.html 을 PC 크롬에서 열면 바로 사용됩니다. 생산 데이터 보관은 그 PC 크롬에 저장됩니다.

■ 앱으로 설치 (권장)
  ※ 불량 히트맵(mapa-defectos) 저장소에는 올리지 마세요. 새 저장소를 만듭니다.
  1) GitHub → + → New repository → 이름 reporte-semanal → Public → Create
  2) 이 폴더의 파일을 모두 올립니다 (index.html, manifest.webmanifest, sw.js, icons 폴더)
  3) Settings → Pages → Branch: main / (root) → Save
  4) 1~2분 뒤 https://doowoncalidadmx-code.github.io/reporte-semanal/ 을 PC 크롬에서 열고
     주소창 오른쪽 '설치' 아이콘 → 설치
  ※ 생산수량·불량 데이터는 GitHub에 올라가지 않고 그 PC 브라우저 안에만 저장됩니다.

■ 처음 한 번
  - 지난주 주간보고 PPT(Reporte_Semanal_…pptx)를 넣으면 전년·누계·전월·지난 4주 실적이 보관됩니다.
    (기준데이터 엑셀 Produccion_PPM.xlsx 를 넣어도 같습니다.)
  - 단가표(스크랩 DB의 COST_REFERENCE 시트가 있는 엑셀)를 넣으면 금액(USD)이 계산됩니다. 한 번 넣으면 기억합니다.

■ 매주
  1) 불량 히트맵 → 지도 탭 → 기간 '전체' (또는 기간 지정으로 최근 2~3개월) → 엑셀 다운로드
  2) 생산관리팀·생산팀 생산실적 파일 (양식 그대로)
     - 일자별 시트(01, 02 … / Start~End 탭)는 각 시트의 날짜로 주차를 자동 계산합니다.
       Start·End 탭 위치를 옮길 필요가 없습니다. 요약 시트(Total·W40·Onepage·Master)는 자동 제외.
     - 생산팀 주간 PPT(Produccion_Semana_xx.ppt)를 그대로 넣어도 됩니다. 안에 붙은 엑셀(일자 시트)을 꺼내 읽습니다.
     - 조립 = ASSY 블록, 융착 = Weld 블록 (HEV·Fan motor·Insertos는 기본 제외 — 화면에서 바꿀 수 있음)
  ※ PPTX 만들기를 누르면 그 주 숫자가 '보고서 값'으로 저장되어, 다음 주 전주 값이 바뀌지 않습니다.
  3) 위 파일들을 한꺼번에 끌어다 놓기 → 주차 선택 → PPTX 만들기
  - 공정을 모르는 라인·품번이 나오면 한 번만 공정을 골라 주면 다음부터 자동입니다.
  - 같은 주차를 두 파일이 다르게 주면 노란 칸에 표시됩니다. '이 파일 우선'으로 기준 파일을 바꿉니다.
  - 수량 열을 잘못 잡았으면 시트 목록에서 수량 열을 골라 주세요 (다음부터 기억).
