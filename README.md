
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Senthamil Selvan | Cinematic Universe</title>
<meta name="theme-color" content="#08090e">
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;700;900&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
:root {
  --red:#ed1c35;
  --blue:#43a5ff;
  --gold:#e8bd72;
  --bg:#08090e;
  --muted:#a4a7b5;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{background:var(--bg);color:#fff;font-family:Inter,sans-serif;overflow-x:hidden}
a{color:inherit;text-decoration:none}
#stars{position:fixed;inset:0;z-index:-2}
body:before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(ellipse at 15% 25%,#5d101d40,transparent 38%),radial-gradient(ellipse at 85% 35%,#063c7140,transparent 40%),linear-gradient(transparent 96%,#ffffff08 97%);background-size:auto,auto,100% 5px}
.nav{position:fixed;top:0;left:0;width:100%;z-index:50;padding:22px 7%;display:flex;justify-content:space-between;align-items:center;background:#08090edb;backdrop-filter:blur(16px);border-bottom:1px solid #ffffff13}
.logo{font-family:Orbitron,sans-serif;font-weight:900;letter-spacing:3px}.logo span{color:var(--red)}
.navlinks{display:flex;gap:30px;font-size:12px;letter-spacing:2px;text-transform:uppercase;color:#c8cad3}
.navlinks a:hover{color:var(--gold)}
.menu{display:none;background:none;color:white;border:1px solid #555;padding:8px 12px}
.hero{min-height:100vh;display:grid;grid-template-columns:1.05fr .95fr;align-items:center;padding:140px 8% 80px;gap:40px;position:relative}
.kicker{color:var(--gold);font-size:11px;letter-spacing:5px;text-transform:uppercase}
h1{font-family:Orbitron,sans-serif;font-size:clamp(42px,6vw,84px);line-height:1.05;letter-spacing:-3px;margin:25px 0}
h1 .red{color:var(--red);text-shadow:0 0 35px #ed1c3540}
h1 .outline{-webkit-text-stroke:1px #ffffffa0;color:transparent}
.typing{font-size:clamp(17px,2vw,23px);color:var(--blue);min-height:32px;margin-bottom:24px}
.intro{max-width:560px;color:#aeb3c1;line-height:1.9;font-size:15px}
.actions{display:flex;flex-wrap:wrap;gap:14px;margin-top:32px}
.btn{padding:14px 21px;font-size:11px;font-weight:700;letter-spacing:2px;text-transform:uppercase;display:inline-block;transition:.3s}
.btn-red{background:var(--red);clip-path:polygon(0 0,92% 0,100% 28%,100% 100%,8% 100%,0 72%)}
.btn-ghost{border:1px solid #ffffff45}
.btn:hover{transform:translateY(-4px);box-shadow:0 0 25px #ed1c3540}
.hero-art{min-height:480px;position:relative;display:grid;place-items:center}
.energy{position:absolute;width:min(420px,80vw);aspect-ratio:1;border-radius:50%;background:radial-gradient(circle,#ed1c3525 0%,#1266b820 35%,transparent 68%);animation:energy 5s infinite alternate}
.ring{position:absolute;width:350px;height:350px;border:1px solid #ed1c3566;border-radius:50%;animation:spin 25s linear infinite}
.ring:before,.ring:after{content:"";position:absolute;inset:22px;border:1px dashed #43a5ff88;border-radius:50%}
.ring:after{inset:60px;border-color:#e8bd7266}
.ring.two{width:280px;height:410px;transform:rotate(60deg);border-color:#43a5ff44;animation:spin 18s linear infinite reverse}
.core{position:relative;width:190px;height:230px;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:10px;filter:drop-shadow(0 0 30px #ed1c3533)}
.core-symbol{font-size:100px;filter:drop-shadow(0 0 20px #ed1c3570)}
.core small{font-family:Orbitron,sans-serif;color:var(--gold);letter-spacing:4px;font-size:10px}
.float-label{position:absolute;padding:12px 15px;background:#101521cc;border:1px solid #ffffff1a;backdrop-filter:blur(8px);font-size:10px;letter-spacing:2px;color:#e5e7ef}
.label1{top:15%;right:0}.label2{bottom:18%;left:0}.label3{top:50%;right:-2%}
.scroll{position:absolute;bottom:25px;left:8%;font-size:9px;letter-spacing:4px;color:#8d92a3}
section{padding:110px 8%}
.section-kicker{text-align:center;color:var(--gold);font-size:10px;letter-spacing:5px;margin-bottom:15px}
h2{text-align:center;font-family:Orbitron,sans-serif;font-size:clamp(27px,4vw,46px);margin-bottom:18px}
h2 span{color:var(--red)}
.sub{text-align:center;max-width:650px;margin:0 auto 55px;color:var(--muted);font-size:14px;line-height:1.8}
.story{display:grid;grid-template-columns:.7fr 1.3fr;gap:55px;align-items:start}
.story-stamp{position:sticky;top:120px;padding:30px;border-left:2px solid var(--red);background:linear-gradient(135deg,#17121a,#0b101a)}
.story-stamp .big{font-family:Orbitron,sans-serif;font-size:48px;color:var(--red)}
.story-stamp p{color:var(--muted);font-size:13px;line-height:1.8;margin-top:12px}
.timeline{position:relative;padding-left:30px}
.timeline:before{content:"";position:absolute;top:0;bottom:0;left:6px;width:1px;background:linear-gradient(var(--red),var(--blue),transparent)}
.event{position:relative;margin-bottom:35px;padding:26px;background:linear-gradient(120deg,#121722e8,#0b0e15e8);border:1px solid #ffffff12;transition:.3s}
.event:hover{border-color:#ed1c3577;transform:translateX(6px)}
.event:before{content:"";position:absolute;left:-31px;top:30px;width:11px;height:11px;background:var(--red);border-radius:50%;box-shadow:0 0 15px var(--red)}
.event .date{font-size:10px;color:var(--gold);letter-spacing:3px}
.event h3{font-family:Orbitron,sans-serif;font-size:17px;margin:12px 0}
.event p{font-size:13px;line-height:1.9;color:var(--muted)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:16px}
.chips span{font-size:10px;padding:7px 9px;background:#ffffff08;border:1px solid #ffffff15;color:#cbd5e1}
.skills{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.skill{padding:28px;background:linear-gradient(145deg,#131722,#0b0d14);border:1px solid #ffffff14;position:relative;overflow:hidden;transition:.3s}
.skill:hover{transform:translateY(-6px);border-color:#43a5ff66}
.skill:after{content:"";position:absolute;top:0;left:0;width:100%;height:2px;background:linear-gradient(90deg,var(--red),var(--blue))}
.skill .icon{font-size:30px;margin-bottom:22px}
.skill h3{font-size:15px;margin-bottom:12px}
.skill p{font-size:12px;color:var(--muted);line-height:1.8}
.skill .num{font-family:Orbitron,sans-serif;color:#ffffff22;font-size:35px;margin-top:22px}
.mission-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:20px}
.mission{display:flex;gap:20px;padding:28px;border:1px solid #ffffff15;background:#10141f;transition:.3s}
.mission:hover{border-color:#e8bd7266}
.mission .num{font-family:Orbitron,sans-serif;color:var(--gold);font-size:23px}
.mission h3{font-size:15px;margin-bottom:10px}
.mission p{font-size:12px;color:var(--muted);line-height:1.8}
.quote{padding:80px 10%;text-align:center;background:linear-gradient(100deg,#350d17,#101b2c,#090b12);border-block:1px solid #ffffff13}
.quote blockquote{font-family:Orbitron,sans-serif;font-size:clamp(18px,3vw,31px);line-height:1.7}
.quote blockquote span{color:var(--gold)}
.quote p{margin-top:20px;color:#aeb3c1;font-size:11px;letter-spacing:4px}
.contact-box{max-width:800px;margin:auto;text-align:center;padding:55px 30px;border:1px solid #ffffff1a;background:radial-gradient(ellipse at top,#1b1722,#0c1019);position:relative}
.contact-box h3{font-family:Orbitron,sans-serif;font-size:clamp(22px,3vw,35px);margin-bottom:18px}
.contact-box p{color:var(--muted);line-height:1.9;font-size:13px}
footer{display:flex;justify-content:space-between;gap:20px;flex-wrap:wrap;padding:25px 8%;border-top:1px solid #ffffff13;color:#858b9b;font-size:10px;letter-spacing:2px}
footer span{color:var(--red)}
.reveal{opacity:0;transform:translateY(25px);transition:opacity .8s,transform .8s}
.reveal.show{opacity:1;transform:translateY(0)}
@keyframes spin{to{transform:rotate(360deg)}}
@keyframes energy{from{transform:scale(.9);opacity:.65}to{transform:scale(1.12);opacity:1}}
@media(max-width:850px){
 .hero{grid-template-columns:1fr;text-align:center;padding-top:140px}
 .intro{margin:auto}.actions{justify-content:center}.hero-art{min-height:400px}
 .story{grid-template-columns:1fr}.story-stamp{position:static}
 .skills{grid-template-columns:repeat(2,1fr)}
 .float-label.label3{right:0}
}
@media(max-width:600px){
 .nav{padding:18px 6%}.menu{display:block}
 .navlinks{display:none;position:absolute;top:100%;left:0;width:100%;background:#090b12;flex-direction:column;padding:20px 7%;gap:22px}
 .navlinks.open{display:flex}
 .hero{padding:125px 6% 60px}
 section{padding:75px 6%}
 .hero-art{min-height:330px;overflow:hidden}
 .ring{width:260px;height:260px}.ring.two{width:220px;height:320px}
 .core-symbol{font-size:75px}
 .float-label{font-size:8px;padding:9px}.label1{right:2%}.label2{left:0}
 .skills,.mission-grid{grid-template-columns:1fr}
 .story{gap:28px}.timeline{padding-left:24px}.event:before{left:-25px}
 .quote{padding:65px 7%}
 footer{padding:25px 6%}
}
@media(prefers-reduced-motion:reduce){
 *,*:before,*:after{animation:none!important;scroll-behavior:auto!important;transition:none!important}
 .reveal{opacity:1;transform:none}
}
</style>
</head>

<body>
<canvas id="stars"></canvas>

<nav class="nav">
  <a href="#home" class="logo">S<span>.</span>S</a>
  <button class="menu" id="menu" aria-label="Open menu">☰</button>
  <div class="navlinks" id="navlinks">
    <a href="#home">Home</a>
    <a href="#story">My Story</a>
    <a href="#experience">Experience</a>
    <a href="#skills">Skills</a>
    <a href="#missions">Projects</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<main>
<section class="hero" id="home">
  <div class="hero-content reveal">
    <p class="kicker">A new chapter begins · Portfolio 2026</p>
    <h1>SENTHAMIL<br><span class="red">SELVAN</span><br><span class="outline">THE JOURNEY</span></h1>
    <div class="typing"><span id="typed"></span> <span style="color:#ed1c35">|</span></div>
    <p class="intro">
      Every great story begins with a challenge. Mine is about understanding
      businesses, solving real problems, and turning complex workflows into
      meaningful solutions through ERP functional consulting.
    </p>
    <div class="actions">
      <a href="#story" class="btn btn-red">Discover My Story ↗</a>
      <a href="#contact" class="btn btn-ghost">Initiate Contact</a>
    </div>
  </div>

  <div class="hero-art reveal">
    <div class="energy"></div>
    <div class="ring"></div>
    <div class="ring two"></div>
    <div class="core">
      <div class="core-symbol">✦</div>
      <small>INITIATE PROTOCOL</small>
    </div>
    <div class="float-label label1">[ SYSTEM ONLINE ]</div>
    <div class="float-label label2">[ BUSINESS × TECHNOLOGY ]</div>
    <div class="float-label label3">[ ERP / FUNCTIONAL ]</div>
  </div>
  <div class="scroll">↓ &nbsp; SCROLL TO EXPLORE THE UNIVERSE</div>
</section>

<section id="story">
  <p class="section-kicker reveal">CHAPTER 01 · THE ORIGIN</p>
  <h2 class="reveal">Every Hero Has A <span>Story</span></h2>
  <p class="sub reveal">Not a story about being perfect. A story about learning, growing, and building a career with purpose.</p>

  <div class="story">
    <aside class="story-stamp reveal">
      <div class="big">01—∞</div>
      <p>THE JOURNEY IS STILL BEING WRITTEN.</p>
      <p>Curiosity became a direction. Challenges became lessons. Every new experience is another chapter.</p>
    </aside>

    <div class="timeline">
      <article class="event reveal">
        <span class="date">CHAPTER 01 · THE FOUNDATION</span>
        <h3>Where It All Began</h3>
        <p>
          My journey into technology and business has been driven by a desire to
          understand how systems work and how technology can improve everyday
          business operations.
        </p>
        <div class="chips"><span>Learning</span><span>Problem Solving</span><span>Curiosity</span></div>
      </article>

      <article class="event reveal">
        <span class="date">CHAPTER 02 · DISCOVERY</span>
        <h3>Connecting Business With Technology</h3>
        <p>
          I developed an interest in business processes, requirements, and ERP
          workflows. I enjoy exploring how teams operate and how a well-designed
          system can make work clearer and more efficient.
        </p>
        <div class="chips"><span>Business Processes</span><span>ERP Concepts</span><span>Analysis</span></div>
      </article>

      <article class="event reveal">
        <span class="date">CHAPTER 03 · THE MISSION</span>
        <h3>ERP Functional Consultant</h3>
        <p>
          My professional focus is on translating business requirements into
          functional solutions, supporting documentation and testing, and
          helping bridge communication between business stakeholders and
          technical teams.
        </p>
        <div class="chips"><span>Requirements</span><span>Documentation</span><span>Testing</span></div>
      </article>

      <article class="event reveal">
        <span class="date">CHAPTER 04 · NEXT LEVEL</span>
        <h3>Building What's Next</h3>
        <p>
          My next chapter is about deepening my ERP knowledge, building stronger
          analytical skills, and contributing to projects that create measurable
          value for businesses.
        </p>
        <div class="chips"><span>Growth</span><span>Innovation</span><span>Impact</span></div>
      </article>
    </div>
  </div>
</section>

<section id="experience">
  <p class="section-kicker reveal">CHAPTER 02 · PROFESSIONAL DOSSIER</p>
  <h2 class="reveal">Experience & <span>Expertise</span></h2>
  <p class="sub reveal">
    A snapshot of the professional capabilities I bring to a team.
    Add your exact companies, dates, ERP products, and achievements below.
  </p>

  <div class="skills">
    <article class="skill reveal">
      <div class="icon">⌘</div>
      <h3>ERP Functional Consulting</h3>
      <p>Understanding business requirements, mapping workflows, and aligning functional processes with business needs.</p>
      <div class="num">01</div>
    </article>
    <article class="skill reveal">
      <div class="icon">◈</div>
      <h3>Business Analysis</h3>
      <p>Gathering stakeholder inputs, identifying gaps, clarifying requirements, and supporting process improvement.</p>
      <div class="num">02</div>
    </article>
    <article class="skill reveal">
      <div class="icon">⌕</div>
      <h3>Functional Documentation</h3>
      <p>Creating structured requirements, process notes, functional specifications, and user documentation.</p>
      <div class="num">03</div>
    </article>
    <article class="skill reveal">
      <div class="icon">⎔</div>
      <h3>Testing & UAT</h3>
      <p>Preparing test scenarios, validating outcomes, recording defects, and supporting user acceptance testing.</p>
      <div class="num">04</div>
    </article>
    <article class="skill reveal">
      <div class="icon">▤</div>
      <h3>Data & Reporting</h3>
      <p>Using spreadsheets and data validation techniques to organize information and support decisions.</p>
      <div class="num">05</div>
    </article>
    <article class="skill reveal">
      <div class="icon">⟡</div>
      <h3>Stakeholder Collaboration</h3>
      <p>Communicating across teams, clarifying expectations, and keeping business and technical work aligned.</p>
      <div class="num">06</div>
    </article>
  </div>
</section>

<section id="missions">
  <p class="section-kicker reveal">CHAPTER 03 · SELECTED MISSIONS</p>
  <h2 class="reveal">Projects & <span>Achievements</span></h2>
  <p class="sub reveal">Replace these sample cards with your real projects and measurable results.</p>

  <div class="mission-grid">
    <article class="mission reveal">
      <div class="num">01</div>
      <div>
        <h3>ERP Process Improvement</h3>
        <p>Describe a workflow you reviewed, a problem you identified, your solution, and the business result.</p>
        <div class="chips"><span>ERP</span><span>Process Mapping</span></div>
      </div>
    </article>
    <article class="mission reveal">
      <div class="num">02</div>
      <div>
        <h3>Requirements & Documentation</h3>
        <p>Show how you collected requirements, prepared documentation, or improved clarity between teams.</p>
        <div class="chips"><span>BRD</span><span>Functional Specs</span></div>
      </div>
    </article>
    <article class="mission reveal">
      <div class="num">03</div>
      <div>
        <h3>Testing & Validation</h3>
        <p>Add an example of test cases, UAT support, defect tracking, or validation you contributed to.</p>
        <div class="chips"><span>UAT</span><span>Quality</span></div>
      </div>
    </article>
    <article class="mission reveal">
      <div class="num">04</div>
      <div>
        <h3>Automation & Reporting</h3>
        <p>Highlight an Excel report, dashboard, data cleanup, or automation that saved time or reduced errors.</p>
        <div class="chips"><span>Excel</span><span>Reporting</span></div>
      </div>
    </article>
  </div>
</section>

<div class="quote reveal">
  <blockquote>“The strongest solution isn't the most complicated one.<br>It's the one that <span>solves the right problem.</span>”</blockquote>
  <p>MY PROFESSIONAL PHILOSOPHY</p>
</div>

<section id="contact">
  <p class="section-kicker reveal">FINAL CHAPTER · YOUR MOVE</p>
  <h2 class="reveal">Let's Build The <span>Next Chapter</span></h2>
  <p class="sub reveal">Open to meaningful conversations about ERP, business processes, collaboration, and opportunities.</p>

  <div class="contact-box reveal">
    <h3>THE NEXT MISSION AWAITS.</h3>
    <p>
      Have an opportunity, project, or idea? Let's talk about how business
      processes and technology can create better outcomes.
    </p>
    <div class="actions" style="justify-content:center">
      <a class="btn btn-red" href="mailto:YOUR_EMAIL@example.com">Send A Message ↗</a>
      <a class="btn btn-ghost" href="https://github.com/YOUR_USERNAME" target="_blank" rel="noopener noreferrer">GitHub Profile ↗</a>
      <a class="btn btn-ghost" href="https://www.linkedin.com/" target="_blank" rel="noopener noreferrer">LinkedIn ↗</a>
    </div>
  </div>
</section>
</main>

<footer>
  <p>© <span id="year"></span> SENTHAMIL SELVAN</p>
  <p>DESIGNED FOR THE <span>NEXT CHAPTER</span></p>
</footer>

<script>
const menu=document.getElementById("menu");
const navlinks=document.getElementById("navlinks");
menu.addEventListener("click",()=>{
  navlinks.classList.toggle("open");
});
navlinks.querySelectorAll("a").forEach(a=>a.addEventListener("click",()=>navlinks.classList.remove("open")));

const phrases=[
  "ERP FUNCTIONAL CONSULTANT",
  "BUSINESS PROCESS ANALYST",
  "REQUIREMENTS & SOLUTIONS",
  "TURNING COMPLEXITY INTO CLARITY"
];
let p=0,c=0,del=false;
const typed=document.getElementById("typed");
function type(){
  const phrase=phrases[p];
  typed.textContent=phrase.substring(0,c);
  if(!del && c<phrase.length){c++;setTimeout(type,65)}
  else if(!del){del=true;setTimeout(type,1400)}
  else if(c>0){c--;setTimeout(type,28)}
  else{del=false;p=(p+1)%phrases.length;setTimeout(type,350)}
}
type();

const observer=new IntersectionObserver(entries=>{
  entries.forEach(entry=>{
    if(entry.isIntersecting){
      entry.target.classList.add("show");
      observer.unobserve(entry.target);
    }
  });
},{threshold:.12});
document.querySelectorAll(".reveal").forEach(el=>observer.observe(el));
document.getElementById("year").textContent=new Date().getFullYear();

// Cinematic starfield
const canvas=document.getElementById("stars");
const ctx=canvas.getContext("2d");
let w,h,stars=[];
const reduced=window.matchMedia("(prefers-reduced-motion: reduce)").matches;

function resize(){
  const ratio=Math.min(window.devicePixelRatio||1,2);
  w=window.innerWidth;h=window.innerHeight;
  canvas.width=w*ratio;canvas.height=h*ratio;
  canvas.style.width=w+"px";canvas.style.height=h+"px";
  ctx.setTransform(ratio,0,0,ratio,0,0);
  stars=Array.from({length:Math.min(180,Math.floor(w*h/6500))},()=>({
    x:Math.random()*w,
    y:Math.random()*h,
    r:Math.random()*1.4+.2,
    a:Math.random(),
    speed:Math.random()*.006+.001
  }));
}
function draw(){
  ctx.clearRect(0,0,w,h);
  for(const s of stars){
    if(!reduced)s.a+=s.speed;
    const alpha=.25+Math.abs(Math.sin(s.a))*.65;
    ctx.beginPath();
    ctx.arc(s.x,s.y,s.r,0,Math.PI*2);
    ctx.fillStyle=`rgba(190,210,255,${alpha})`;
    ctx.fill();
  }
  if(!reduced)requestAnimationFrame(draw);
}
window.addEventListener("resize",resize);
resize();draw();
</script>
</body>
</html>
