<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>Special Message</title>

<style>
body {
    margin: 0;
    font-family: Arial;
    text-align: center;
    background: black;
    color: pink;
}

/* إخفاء الصفحات */
.screen {
    display: none;
    padding: 50px;
}

/* الصفحة النشطة */
.active {
    display: block;
}

/* زر */
button {
    padding: 10px 20px;
    font-size: 18px;
    border: none;
    background: pink;
    cursor: pointer;
    border-radius: 10px;
}

/* القلوب */
.heart {
    position: fixed;
    top: -10px;
    font-size: 20px;
    animation: fall linear infinite;
}

@keyframes fall {
    to {
        transform: translateY(100vh);
    }
}
</style>
</head>

<body>

<!-- الصفحة 1 -->
<div id="screen1" class="screen active">
    <h2>أدخل اسمك</h2>
    <input type="text" id="name">
    <br><br>
    <button onclick="checkName()">دخول</button>
</div>

<!-- الصفحة 2 -->
<div id="screen2" class="screen">
    <p>so it's you , it's you who biber talk me about</p>
    <p>okey , you have a letter from him</p>
    <button onclick="nextScreen(3)">اضغط</button>
</div>

<!-- الصفحة 3 -->
<div id="screen3" class="screen">
    <h2>💖 3 reasons why i love you 💖</h2>
    <button onclick="nextScreen(4)">التالي</button>
</div>

<!-- الصفحة 4 -->
<div id="screen4" class="screen">
    <h2>Your eyes 💖</h2>
    <button onclick="nextScreen(5)">التالي</button>
</div>

<!-- الصفحة 5 -->
<div id="screen5" class="screen">
    <h2>Your smile 💖</h2>
    <button onclick="nextScreen(6)">التالي</button>
</div>

<!-- الصفحة 6 -->
<div id="screen6" class="screen">
    <h2>wait only 3 ??</h2>
    <button onclick="nextScreen(7)">التالي</button>
</div>

<!-- الصفحة 7 -->
<div id="screen7" class="screen">
    <h2>Your laught 💞
Your personality 💞
Your hair 💞
Your humor 💞
Your voice 💞
Your style 💞
Your name 💞
The way you treat me 💞
Your kindness 💞
The way you care 💞
How easily you make me laugh 💞
Our late-night calls 💞
Our calls in general 💞
The way you laugh with me 💞
How you motivate me 💞
The way you talk to me 💞
Your honesty 💞
Your loyalty 💞
How strong you are 💞
How quickly we clicked 💞
Finding my best friend in you 💞
The peace I found talking to you 💞
Seeing my future in your eyes 💞
How fun you are 💞
The way you appreciate everything 💞
Your gratefulness 💞
How you never doubt me 💞
The way you support me 💞
How proud you are of me 💞
Always being by my side 💞
Loving me unconditionally 💞
Making me feel enough 💞
Making me feel worth it 💞
Inspiring me 💞
Helping me become better 💞
Changing my view on the world 💞
Staying even when things are hard 💞
Teaching me things 💞
Never getting disappointed in me 💞
Talking calmly 💞
Never giving up 💞
Making me feel so loved 💞
Making me feel cared for 💞
Always being there for me 💞
The way you treat people 💞
Your love for kids 💞
The way you treat animals 💞
Always thinking of me 💞
Trying your best 💞
Being a bad influence (in a fun way) 💞
Being comfortable in silence with you 💞
Never being aggressive without a reason 💞
Always being motivated 💞
Having a reason for everything 💞
Trying to make people happy 💞
How you see things 💞
Making me so happy 💞
Giving me a reason 💞
Your lips 💞
Your presence 💞
Keeping your promises 💞
Being reliable 💞
Helping me 💞
Being sweet 💞
Being kind 💞
Being calm even when it’s stressful 💞
Talking to you feels right 💞
Being my soulmate 💞
Giving me special memories 💞
Loving every moment with you 💞
Our communication 💞
Being committed 💞
Being disciplined 💞
Loving me for more than just my body 💞
Believing in me 💞
Believing in yourself 💞
Being mostly positive 💞
Being perfect in your own way 💞
Never getting bored of me 💞
Never getting annoyed at me 💞
The names you call me 💞
Making me feel special 💞
Appreciating small things 💞
Your giggles 💞
Always understanding me 💞
The glow in your eyes 💞
Being happy even for the smallest things 💞
Not caring if I have money 💞
Calling me when I ask 💞
Never going to bed angry 💞
Your hugs 💞
Calling me if I’m upset 💞
Helping me when I’m upset 💞
Not giving up on your goals 💞
Giving me hope 💞
Making life easier 💞
Making life feel worth it 💞
Being my safe place 💞</h2>
</div>

<script>
// التحقق من الاسم
function checkName() {
    let name = document.getElementById("name").value;

    if (name === "مروى") {
        nextScreen(2);
    } else {
        alert("هذا الموقع ليس لك 😅");
    }
}

// تغيير الصفحات
function nextScreen(num) {
    document.querySelectorAll(".screen").forEach(s => s.classList.remove("active"));
    document.getElementById("screen" + num).classList.add("active");

    if (num >= 3) {
        startHearts();
    }
}

// القلوب المتساقطة
function startHearts() {
    setInterval(() => {
        let heart = document.createElement("div");
        heart.className = "heart";
        heart.innerHTML = "💖";

        heart.style.left = Math.random() * 100 + "vw";
        heart.style.animationDuration = (Math.random() * 3 + 2) + "s";

        document.body.appendChild(heart);

        setTimeout(() => {
            heart.remove();
        }, 5000);
    }, 300);
}
</script>

</body>
</html>

