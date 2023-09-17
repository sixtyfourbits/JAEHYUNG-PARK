<script>

    import { text } from "@sveltejs/kit";

</script>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JAEHYUNG'S PORTFOLIO</title>
    <link href='https://fonts.googleapis.com/css?family=Fira Code' rel='stylesheet'>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Foldit:wght@300;400;500;600&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=VT323&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;1,100;1,200;1,300;1,400;1,500&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans+KR:wght@100;200;300;400;500;600;700&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap');

        .normal {
            font-family: 'IBM Plex Mono', 'IBM Plex Sans KR', 'VT323';
            text-align: center;
            font-weight: 500;
            font-size: 15px;
        }

		.flex {
			display: flex;
			justify-content: center;
			align-items: center;
		}
        
        body {
            padding: 10px 200px;
            text-align: center;
			background-color: #f0f0f0;
        }
        name {
            font-family: 'IBM Plex Mono', 'IBM Plex Sans KR', 'VT323';
            font-weight: bold;
            font-size: 30px;
        }

        nickname {
            font-family: 'Foldit';
            font-weight: bold;
            font-size: 20px;
        }
    </style>
</head>
<body>
    <div style="margin: 128px 0px;">
        <name>JAEHYUNG PARK</name>
        <br>
        <nickname>AKA; SIXTYFOURBITS</nickname>
        <div class="normal">
            <br>
            Hello, I'm just a student who like coding very much.
			<br>
			<br>
			I purpose is to <span style="font-weight:900; font-style: italic">give people wonderful things. Make the world better.</span>
        </div>
        <div class="normal" style="margin-top: 300px">
            <span style="font-size: 20px;">Skills</span>
            <br>
			<br>
            <div class="flex" style="text-align: left">
			<span style="text-align: left">
			🏅 2022 한국정보올림피아드 중등부 1차 대회 전국 부문 장려상 ( KOI 1st Competition Encouragement Award )
			<br>
			🥉 2023 한국정보올림피아드 중등부 1차 대회 전국 부문 동상 ( KOI 1st Competition Bronze Award )
			<br>
			🥈 2023 한국정보올림피아드 중등부 2차 대회 은상 <tmp style="font-style:italic">27th</tmp>  ( KOI 2nd Competition Silver Award )
			</span>
            </div>
        </div>
    </div>
</body>
</html>
