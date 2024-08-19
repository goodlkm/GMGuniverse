<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<title>자동 조 구성 프로그램</title>
<style>
    .participant { margin-bottom: 10px; display: flex; align-items: center; }
    .container {
        display: flex;
        justify-content: space-between;
    }
    #resultsLeft, #resultsRight {
        flex: 1;
        padding: 10px;
        border: 1px solid #ccc;
        margin: 5px;
    }
    input[type="text"], select, button {
        margin-right: 10px;
        margin-bottom: 10px;
    }
</style>
<script>
var participants = [
{ name: "백윤진전도사님", gender: "남", hasCar: false, participating: true },
    { name: "오지수팀장님", gender: "여", hasCar: false, participating: true },
    { name: "ahn Heejoo", gender: "여", hasCar: false, participating: true },
    { name: "강은새", gender: "여", hasCar: false, participating: true },
    { name: "강다은", gender: "여", hasCar: false, participating: true },
    { name: "강예슬", gender: "여", hasCar: false, participating: true },
    { name: "김동형팀장님", gender: "남", hasCar: false, participating: true },
    { name: "구가영", gender: "여", hasCar: false, participating: true },
    { name: "권보현", gender: "여", hasCar: false, participating: true },
    { name: "기인학", gender: "남", hasCar: false, participating: true },
    { name: "김다현", gender: "여", hasCar: false, participating: true },
    { name: "김미지", gender: "여", hasCar: false, participating: true },
    { name: "김보민", gender: "여", hasCar: false, participating: true },
    { name: "김수현", gender: "여", hasCar: false, participating: true },
    { name: "김예진", gender: "여", hasCar: false, participating: true },
    { name: "김지혜", gender: "여", hasCar: false, participating: true },
    { name: "김가연", gender: "여", hasCar: false, participating: true },
    { name: "김나영", gender: "여", hasCar: false, participating: true },
    { name: "김도영", gender: "여", hasCar: false, participating: true },
    { name: "김민주", gender: "여", hasCar: false, participating: true },
    { name: "김화람", gender: "여", hasCar: false, participating: true },
    { name: "남민주", gender: "여", hasCar: false, participating: true },
    { name: "류지민", gender: "여", hasCar: false, participating: true },
    { name: "배수빈", gender: "여", hasCar: false, participating: true },
    { name: "탁민호생도님", gender: "남", hasCar: false, participating: true },
    { name: "심은서", gender: "여", hasCar: false, participating: true },
    { name: "유혜린", gender: "여", hasCar: false, participating: true },
    { name: "윤다원", gender: "여", hasCar: false, participating: true },
    { name: "윤세영", gender: "여", hasCar: false, participating: true },
    { name: "이혜빈", gender: "여", hasCar: false, participating: true },
    { name: "이가은", gender: "여", hasCar: false, participating: true },
    { name: "이다연", gender: "여", hasCar: false, participating: true },
    { name: "이미현", gender: "여", hasCar: false, participating: true },
    { name: "이수영", gender: "여", hasCar: false, participating: true },
    { name: "이승규", gender: "남", hasCar: false, participating: true },
    { name: "이연미", gender: "여", hasCar: false, participating: true },
    { name: "이재영", gender: "남", hasCar: false, participating: true },
    { name: "이정수간사님", gender: "여", hasCar: false, participating: true },
    { name: "이효리", gender: "여", hasCar: false, participating: true },
    { name: "임수미", gender: "여", hasCar: false, participating: true },
    { name: "임재민", gender: "남", hasCar: false, participating: true },
    { name: "장서영", gender: "여", hasCar: false, participating: true },
    { name: "정다혜", gender: "여", hasCar: false, participating: true },
    { name: "정환희", gender: "남", hasCar: false, participating: true },
    { name: "조서영", gender: "여", hasCar: false, participating: true },
    { name: "김진솔", gender: "여", hasCar: false, participating: true },
    { name: "강민기생도님", gender: "남", hasCar: false, participating: true },
    { name: "?채영", gender: "여", hasCar: false, participating: true },
    { name: "김태형생도님", gender: "남", hasCar: false, participating: true },
    { name: "최미소", gender: "여", hasCar: false, participating: true },
    { name: "최세연", gender: "여", hasCar: false, participating: true },
    { name: "최예린", gender: "여", hasCar: false, participating: true },
    { name: "최유리", gender: "여", hasCar: false, participating: true },
    { name: "김규리", gender: "여", hasCar: false, participating: true },
    { name: "문서영", gender: "여", hasCar: false, participating: true },
    { name: "한새하", gender: "여", hasCar: false, participating: true },
    { name: "한은비", gender: "여", hasCar: false, participating: true },
    { name: "함수빈", gender: "여", hasCar: false, participating: true },
    { name: "?해솔", gender: "여", hasCar: false, participating: true },
    { name: "홍나리", gender: "여", hasCar: false, participating: true },
    { name: "홍현지간사님", gender: "여", hasCar: false, participating: true },
    { name: "황유진", gender: "여", hasCar: false, participating: true },
    { name: "이경민", gender: "남", hasCar: false, participating: true },
];

function displayParticipants() {
    var list = document.getElementById('participantList');
    list.innerHTML = ''; // 리스트 초기화
    participants.forEach(function(participant, index) {
        var div = document.createElement('div');
        div.className = 'participant';

        var info = document.createElement('span');
        info.textContent = `${participant.name} (${participant.gender}) - `;

        var carCheckbox = document.createElement('input');
        carCheckbox.type = 'checkbox';
        carCheckbox.checked = participant.hasCar;
        carCheckbox.onchange = function() { participants[index].hasCar = this.checked; };
        var carLabel = document.createElement('label');
        carLabel.textContent = '차량 보유 ';
        carLabel.appendChild(carCheckbox);

        var participatingCheckbox = document.createElement('input');
        participatingCheckbox.type = 'checkbox';
        participatingCheckbox.checked = participant.participating;
        participatingCheckbox.onchange = function() { participants[index].participating = this.checked; };
        var participatingLabel = document.createElement('label');
        participatingLabel.textContent = '참여 ';
        participatingLabel.appendChild(participatingCheckbox);

        div.appendChild(info);
        div.appendChild(carLabel);
        div.appendChild(participatingLabel);
        list.appendChild(div);
    });
}

function addParticipant() {
    var name = document.getElementById('newName').value;
    var gender = document.getElementById('newGender').value;
    var hasCar = document.getElementById('newHasCar').checked;
    var participating = document.getElementById('newParticipating').checked;

    participants.push({ name: name, gender: gender, hasCar: hasCar, participating: participating });
    displayParticipants(); // Update list
    document.getElementById('newName').value = ''; // Reset input fields
    document.getElementById('newHasCar').checked = false;
    document.getElementById('newParticipating').checked = true;
}

function shuffle(array) {
    for (let i = array.length - 1; i > 0; i--) {
        const j = Math.floor(Math.random() * (i + 1));
        [array[i], array[j]] = [array[j], array[i]]; // swap elements
    }
}

function generateTeams() {
    var filteredParticipants = participants.filter(p => p.participating);
    shuffle(filteredParticipants);

    var teams = [];
    var currentTeam = [];
    filteredParticipants.forEach(function(participant) {
        currentTeam.push(`${participant.name} (${participant.gender})`);
        if (currentTeam.length === 3) {
            teams.push(currentTeam);
            currentTeam = [];
        }
    });

    if (currentTeam.length > 0) { // 마지막 팀 처리
        teams.push(currentTeam);
    }

    var resultsLeftDiv = document.getElementById('resultsLeft');
    var resultsRightDiv = document.getElementById('resultsRight');
    resultsLeftDiv.innerHTML = '';
    resultsRightDiv.innerHTML = ''; // 결과 초기화
    teams.forEach((team, index) => {
        var p = document.createElement('p');
        p.textContent = '팀 ' + (index + 1) + ': ' + team.join(', ');
        if (index % 2 === 0) {
            resultsLeftDiv.appendChild(p);
        } else {
            resultsRightDiv.appendChild(p);
        }
    });
}

document.addEventListener('DOMContentLoaded', function() {
    displayParticipants();
});
</script>
</head>
<body>
<h1>자동 조 구성 프로그램</h1>
<div>
    <input type="text" id="newName" placeholder="이름">
    <select id="newGender">
        <option value="남">남</option>
        <option value="여">여</option>
    </select>
    <label><input type="checkbox" id="newHasCar"> 차량 보유</label>
    <label><input type="checkbox" id="newParticipating" checked> 참여</label>
    <button onclick="addParticipant()">참가자 추가</button>
</div>
<div id="participantList"></div>
<button onclick="generateTeams()">조 추첨</button>
<div class="container">
    <div id="resultsLeft"></div>
    <div id="resultsRight"></div>
</div>
</body>
</html>
