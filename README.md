<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>서울시, 도심·환승역 주변 고밀복합개발 본격 추진</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700;900&family=Noto+Serif+KR:wght@700;900&display=swap');
        
        * { box-sizing: border-box; margin: 0; padding: 0; }
        
        body {
            font-family: 'Noto Sans KR', sans-serif;
            background-color: #f1f5f9;
            color: #1e293b;
            padding: 40px 20px;
            line-height: 1.7;
        }

        /* 공문서 스타일 A4 레이아웃 컨테이너 */
        .document-page {
            max-width: 820px;
            margin: 0 auto 30px auto;
            background: #ffffff;
            padding: 60px 50px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.05);
            border: 1px solid #e2e8f0;
            position: relative;
        }

        /* 상단 타이틀 매칭 */
        .doc-header-top {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 2px solid #000;
            padding-bottom: 12px;
            margin-bottom: 20px;
        }
        .corporate-title {
            font-size: 13px;
            font-weight: 700;
            letter-spacing: 1px;
            color: #0f172a;
        }
        .release-date-status {
            text-align: right;
            font-size: 12px;
            font-weight: bold;
            color: #1e3a8a;
        }

        /* 보도자료 메인 헤더 및 담당부서 표 */
        .press-main-title-area {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            margin-bottom: 35px;
            gap: 20px;
        }
        .seoul-logo-section {
            display: flex;
            flex-direction: column;
            gap: 4px;
            margin-top: 10px;
        }
        .logo-txt-top {
            font-family: 'Noto Serif KR', serif;
            font-size: 26px;
            font-weight: 900;
            letter-spacing: -1px;
            color: #dc2626;
            line-height: 1.1;
        }
        .logo-txt-bottom {
            font-size: 24px;
            font-weight: 900;
            color: #1e3a8a;
            line-height: 1.1;
            letter-spacing: 2px;
        }
        .press-badge {
            font-family: 'Noto Serif KR', serif;
            font-size: 34px;
            font-weight: 900;
            border: 3px double #000;
            padding: 2px 14px;
            letter-spacing: 6px;
            color: #000;
            margin-left: 10px;
            margin-top: 5px;
        }

        /* 담당부서 테이블 구조 복원 */
        .department-table {
            border-collapse: collapse;
            font-size: 12px;
            width: 320px;
        }
        .department-table th, .department-table td {
            border: 1px solid #000;
            padding: 6px 8px;
            text-align: left;
            height: 28px;
        }
        .department-table th {
            background-color: #f8fafc;
            font-weight: 600;
            text-align: center;
        }

        /* 핵심 대제목 박스 */
        .headline-box {
            border: 4px double #000;
            padding: 18px 24px;
            text-align: center;
            margin-bottom: 40px;
            background: #fff;
        }
        .headline-box h2 {
            font-family: 'Noto Sans KR', sans-serif;
            font-weight: 900;
            font-size: 23px;
            line-height: 1.4;
            color: #000;
            letter-spacing: -0.5px;
        }

        /* 본문 공문서식 조판 기호 마진 설정 */
        .content-body {
            text-align: justify;
            word-break: break-all;
            font-size: 15px;
            color: #111111;
        }
        
        /* ⬛ 대문단 구조 */
        .para-main {
            position: relative;
            padding-left: 24px;
            margin-bottom: 25px;
            font-weight: 700;
            font-size: 16px;
        }
        .para-main::before {
            content: "⬛";
            position: absolute;
            left: 0;
            top: 2px;
            font-size: 14px;
            color: #000;
        }

        /* ❍ 중문단 구조 */
        .para-sub {
            position: relative;
            padding-left: 24px;
            margin-left: 24px;
            margin-bottom: 18px;
            font-weight: 500;
        }
        .para-sub::before {
            content: "❍";
            position: absolute;
            left: 0;
            top: 1px;
            font-size: 14px;
            font-weight: bold;
        }

        /* – 소문단 구조 */
        .para-detail {
            position: relative;
            padding-left: 20px;
            margin-left: 48px;
            margin-bottom: 14px;
            color: #334155;
            font-weight: 400;
        }
        .para-detail::before {
            content: "–";
            position: absolute;
            left: 0;
            top: -1px;
            font-weight: bold;
        }

        /* 주석 기호 설정 */
        .para-note {
            position: relative;
            padding-left: 20px;
            margin-left: 48px;
            margin-bottom: 14px;
            color: #475569;
            font-size: 14px;
        }
        .para-note::before {
            content: "○";
            position: absolute;
            left: 0;
            top: 1px;
        }

        /* 공문서 하단 페이지 번호 */
        .page-footer-num {
            text-align: center;
            font-size: 12px;
            color: #64748b;
            margin-top: 50px;
            font-family: sans-serif;
            letter-spacing: 4px;
        }
    </style>
</head>
<body>

    <!-- PAGE 1 -->
    <div class="document-page">
        <div class="doc-header-top">
            <div class="corporate-title">SUNGWONSPACE ㈜성원스페이스</div>
            <div class="release-date-status">
                2026. 6. 1.(월) 조간용<br>
                <span style="font-weight: normal; font-size: 11px; color: #64748b;">이 보도자료는 2026년 5월 31일 오전 11:15부터 보도할 수 있습니다.</span>
            </div>
        </div>

        <div class="press-main-title-area">
            <div class="flex items-center">
                <div class="seoul-logo-section">
                    <span class="logo-txt-top">동행·매력 특별시</span>
                    <span class="logo-txt-bottom">서울</span>
                </div>
                <div class="press-badge">보도자료</div>
            </div>
            
            <table class="department-table">
                <tr>
                    <th>담당 부서</th>
                    <td>도시공간본부 도시공간전략과</td>
                    <th>도시공간전략과장</th>
                    <td>김창기</td>
                    <td>02-2133-6960</td>
                </tr>
                <tr>
                    <th>문의 사항</th>
                    <td>보도 배포 및 총괄 담당</td>
                    <th>종합계획팀장</th>
                    <td>고경곤</td>
                    <td>02-2133-6980</td>
                </tr>
            </table>
        </div>

        <div class="headline-box">
            <h2>서울시, 도심·환승역 주변 고밀복합개발 본격 추진<br>용적률 ‘최대 1300%’ 적용</h2>
        </div>

        <div class="content-body">
            <div class="para-detail" style="margin-left: 0; margin-bottom: 30px; font-weight: 500; font-size: 15.5px; line-height: 1.8;">
                도시 광문교통망 및 주요 관문 역세권 구역을 업무·고밀 복합거점으로 육성<br>
                일반상업지역 및 준주거지역 상향을 통해 용적률 최대 1,300% 적용, 대규모 고밀개발 유도<br>
                성장거점형 복합개발사업 운영기준 마련… 시범사업 통해 제도 안착 추진<br>
                6월 후보지 추천 및 시범사업 착수… 서울형 복합개발 모델 본격 본격화
            </div>

            <div class="para-main">
                서울시가 중심지 및 환승역 주변을 교통·업무·상업·주거가 테마가 어우러진 고밀복합 거점으로 조성하기 위해 「성장거점형 복합개발사업」을 본격 추진한다.
            </div>

            <div class="para-sub">
                이번 사업은 대중교통구역 전반의 복합적 육성이 필요한 중심지역의 대중교통 접근성이 우수한 환승역 주변에 대한 다양한 도시기능을 복합적으로 유도하여, 기존 도심 기능을 고도화하고 새로운 성장거점을 조성하는 것을 목표로 한다.
            </div>

            <div class="para-detail">
                사업 여건과 입지 특성 등을 고려해 관련 기준에 따라 일반상업지역으로 용도지역을 상향하는 경우 용적률을 최대 1,300%까지 적용할 수 있도록 하여, 업무·상업·상업·주거·문화 기능이 집약된 고밀복합 개발을 유도한다.
            </div>
        </div>
        <div class="page-footer-num">- 1 -</div>
    </div>

    <!-- PAGE 2 -->
    <div class="document-page">
        <div class="content-body" style="padding-top: 30px;">
            <div class="para-detail" style="margin-left: 24px;">
                사업대상지는 서울도시기본계획상 중심지·광역중앙 및 대중교통 접근성이 우수한 환승역 반경 500m 이내 영역을 중심으로 설정된다.
            </div>

            <div class="para-main">
                서울시는 그간 「도심 복합개발 지원에 관한 법률」에 따라 조례와 시행규칙을 제정하여 제도적 기반을 구축해 왔으며, 원활한 사업 추진을 위해 「성장거점형 복합개발사업 운영기준」을 새롭게 마련했다.
            </div>

            <div class="para-sub">
                이번 운영기준에는 사업대상지 요건, 복합개발계획 수립기준, 용도지역 상향기준, 공공기여 산정 기준 등 사업 추진을 위한 세부 기준이 담겼다.
            </div>

            <div class="para-sub">
                특히, 서울시는 자치구 및 민간개발 사업 신청 제공을 위해 지역 여건을 고려한 공공기여 이중 완화 기준을 마련했다.
            </div>

            <div class="para-detail">
                용도지역 변경에 따른 공공기여 비율은 공공기여 적용률의 50%를 기본으로 적용하되, 필요시 자치구에서 관할 자치구의 비율을 최대 10% 범위 안에서 지역 여건에 따라 인하 조정할 수 있도록 하여 사업성을 대폭 제고했다. 이는 상대적으로 개발 여건이 부족한 지역의 사업 부담을 낮춰주고, 민간 참여 및 사업 추진 가능성을 높이기 위한 취지다.
            </div>

            <div class="para-detail">
                「성장거점형 복합개발사업 운영기준」의 세부내용은 서울시도시계획포털 누리집 자료실에서 확인할 수 있다.
            </div>

            <div class="para-main">
                서울시는 6월부터 자치구로부터 후보지를 추천받아 개발지 대상지의 적정성을 검토하고, 시범사업 대상지를 선정할 예정이다.
            </div>

            <div class="para-sub">
                자치구가 지역 여건과 개발 필요성, 사업 실현 가능성 등을 종합적으로 검토해 후보지를 추천하면, 서울시가 전문가 자문 등을 거쳐 최종 대상지를 선정하게 된다.
            </div>

            <div class="para-sub">
                서울시는 제도의 안정적 안착을 위해 우선 시범사업을 추진하고, 운영 과정에서 나타나는 미비점을 지속적으로 보완해 나갈 계획이다.
            </div>
        </div>
        <div class="page-footer-num">- 2 -</div>
    </div>

    <!-- PAGE 3 -->
    <div class="document-page">
        <div class="content-body" style="padding-top: 30px;">
            <div class="para-main">
                서울시는 이번 사업을 통해 중심지역과 환승역 주변의 입지적 장점을 적극 활용하고, 도시 기능 강화가 필요한 지역을 고밀복합 거점으로 전환하여 서울 전역의 균형 있는 성장을 도모한다는 방침이다.
            </div>

            <div class="para-sub">
                이를 통해 지역 내 일자리·주거·문화·생활편의 기능을 확충하고, 기반시설 여건을 개선해 서울의 도시경쟁력 제고에도 크게 기여할 것으로 기대된다.
            </div>

            <div class="para-main" style="margin-top: 40px; border-left: 4px solid #c9a84c; padding-left: 16px;">
                조남준 서울시 도시공간본부장은 “성장거점형 복합개발사업은 중심지와 환승역 주변의 잠재력을 활용해 서울의 새로운 활력을 불어넣는 핵심 사업”이라며, “시범사업을 통해 제도의 실효성을 검증하고, 공공성과 사업성이 균형을 이루는 서울형 복합개발 모델을 마련해 나가겠다”고 말했다.
            </div>
        </div>
        
        <!-- 하단 기관 주소 여백 바닥글 복원 -->
        <div style="margin-top: 180px; border-top: 1px solid #cbd5e1; pt-4; text-align: center; font-size: 11px; color: #94a3b8;">
            SUNGWONSPACE ㈜성원스페이스 &nbsp;|&nbsp; 서울시 동작구 동작대로 37, 3층
        </div>
        <div class="page-footer-num">- 3 -</div>
    </div>

</body>
</html>
