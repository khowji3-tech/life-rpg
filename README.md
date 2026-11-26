# life-rpg
Personal LIFE RPG
<!doctype html>
<html lang="fa" dir="rtl">
<head><link rel="icon" type="image/png" href="./icon.png">
<link rel="apple-touch-icon" href="./icon.png">
 
<meta charset="utf-8"><meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<meta name="theme-color" content="#0b1020"><title>LIFE RPG | زندگی، بازی تو</title>
<style>
:root{--bg:#090d18;--panel:#111827;--panel2:#172033;--line:#263248;--txt:#eef2ff;--muted:#9aa7bd;--purple:#a78bfa;--blue:#60a5fa;--green:#34d399;--gold:#fbbf24;--red:#fb7185}
*{box-sizing:border-box}body{margin:0;background:radial-gradient(ellipse at top,#18213a 0,#090d18 52%);color:var(--txt);font-family:Tahoma,Arial,sans-serif;font-size:14px;line-height:1.8}button,input,select,textarea{font:inherit}button{cursor:pointer;border:0;color:inherit}.wrap{max-width:850px;margin:auto;padding:18px 14px 90px}.top{display:flex;justify-content:space-between;align-items:center;margin:5px 0 18px}.brand{font-size:21px;font-weight:900;letter-spacing:.5px}.brand span{color:var(--purple)}.pill{border:1px solid var(--line);background:#121a2b;color:var(--muted);border-radius:30px;padding:5px 10px;font-size:11px}.hero,.card{background:linear-gradient(145deg,#151e31,#101726);border:1px solid var(--line);border-radius:19px;padding:17px;margin-bottom:14px;box-shadow:0 10px 35px #0003}.hero{background:linear-gradient(120deg,#24204a,#15233c 58%,#102b32)}.eyebrow{color:#c4b5fd;font-size:11px;font-weight:bold}.levelrow{display:flex;align-items:center;gap:13px;margin:9px 0}.level{font-size:37px;font-weight:900;line-height:1.2}.level small{font-size:12px;color:var(--muted)}.xp{color:#ddd6fe;font-size:12px}.bar{height:9px;background:#293449;border-radius:20px;overflow:hidden}.bar i{display:block;height:100%;border-radius:20px;background:linear-gradient(90deg,#8b5cf6,#38bdf8);width:0;transition:width .3s}.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:9px;margin-top:14px}.stat{background:#0c1423a8;border:1px solid #ffffff12;border-radius:13px;padding:10px}.stat b{display:block;font-size:20px}.stat span{color:var(--muted);font-size:11px}.sectionhead{display:flex;align-items:center;justify-content:space-between;margin:18px 2px 10px}.sectionhead h2{font-size:16px;margin:0}.muted{color:var(--muted)}.skills{display:grid;grid-template-columns:repeat(3,1fr);gap:9px}.skill{background:#111a2a;border:1px solid var(--line);border-radius:15px;padding:12px}.skill .emoji{font-size:21px}.skill strong{display:block;margin:4px 0}.skill small{color:var(--muted);font-size:11px}.skill .bar{margin-top:9px;height:6px}.skill .bar i{background:var(--c)}.tabs{display:flex;gap:7px;overflow:auto;padding:5px 0 13px;position:sticky;top:0;background:#090d18ee;z-index:5}.tab{white-space:nowrap;border:1px solid var(--line);background:#111827;border-radius:30px;padding:8px 13px;color:var(--muted);font-size:12px}.tab.active{background:#6d4bc4;color:white;border-color:#8b5cf6}.task{display:flex;align-items:flex-start;gap:10px;background:#111a2a;border:1px solid var(--line);border-radius:13px;padding:11px;margin:8px 0}.task input{accent-color:#a78bfa;width:18px;height:18px;margin-top:5px}.task.done{opacity:.55}.task.done .taskname{text-decoration:line-through}.taskmain{flex:1}.taskname{font-weight:bold}.taskmeta{font-size:11px;color:var(--muted)}.tag{font-size:10px;color:#ddd6fe;background:#30264d;padding:3px 7px;border-radius:20px}.actions{display:flex;gap:7px;flex-wrap:wrap;margin-top:12px}.btn{padding:9px 13px;border-radius:11px;background:#6d4bc4;font-weight:bold;font-size:12px}.btn.secondary{background:#202b40;border:1px solid var(--line)}.btn.danger{background:#542638}.btn.green{background:#12634e}.formgrid{display:grid;grid-template-columns:1fr 1fr;gap:9px}.field{display:flex;flex-direction:column;gap:4px}.field.full{grid-column:1/-1}.field label{font-size:11px;color:var(--muted)}input,select,textarea{background:#0b1321;border:1px solid var(--line);border-radius:10px;color:var(--txt);padding:10px;min-width:0;width:100%}input[type=checkbox]{width:auto}.listrow{display:flex;justify-content:space-between;align-items:center;padding:10px 0;border-bottom:1px solid #ffffff10;gap:10px}.listrow:last-child{border:0}.node{border:1px solid var(--line);background:#111a2a;border-radius:12px;padding:12px;margin:8px 0}.node.unlocked{border-color:#7c5bd2;background:#211b38}.node small{display:block;color:var(--muted)}.badge{color:#fcd34d;font-size:11px}.hidden{display:none!important}.empty{text-align:center;color:var(--muted);padding:22px}.toast{position:fixed;bottom:20px;left:50%;transform:translateX(-50%);background:#24324a;padding:10px 16px;border:1px solid #52617a;border-radius:30px;display:none;z-index:10}.footer{text-align:center;color:#718096;font-size:10px;margin-top:25px}
@media(max-width:520px){.wrap{padding:12px 11px 80px}.skills{grid-template-columns:1fr 1fr}.stats{gap:6px}.stat{padding:8px}.stat b{font-size:17px}.hero,.card{padding:14px}.formgrid{grid-template-columns:1fr 1fr}}
</style></head>
<body><main class="wrap">
<header class="top"><div class="brand">LIFE <span>RPG</span></div><div class="pill" id="dateLabel">فصل اول · بازسازی</div></header>
<section class="hero">
 <div class="eyebrow">SEASON 01 · THE REBUILD</div><div class="levelrow"><div class="level" id="level">LV. 1</div><div><div class="xp" id="totalXp">۰ XP کل</div><small class="muted" id="rank">تازه‌وارد</small></div></div>
 <div class="bar"><i id="levelBar"></i></div><div class="xp" id="levelProgress" style="margin-top:6px">۰ / ۱۰۰ XP تا لول بعد</div>
 <div class="stats"><div class="stat"><b id="todayCount">۰</b><span>مأموریت امروز</span></div><div class="stat"><b id="streak">۰</b><span>روز فعال پیاپی</span></div><div class="stat"><b id="weekXp">۰</b><span>XP این هفته</span></div></div>
</section>
<div class="sectionhead"><h2>⚔️ مهارت‌های اصلی</h2><span class="muted" style="font-size:11px">هر مهارت لول مستقل دارد</span></div>
<section class="skills" id="skills"></section>
<nav class="tabs">
<button class="tab active" data-tab="today">امروز</button><button class="tab" data-tab="quests">مأموریت‌ها</button><button class="tab" data-tab="tree">درخت مهارت</button><button class="tab" data-tab="rewards">پاداش‌ها</button><button class="tab" data-tab="report">گزارش</button><button class="tab" data-tab="settings">تنظیمات</button>
</nav>
<section id="today" class="panel">
 <div class="sectionhead"><h2>🎯 مأموریت‌های امروز</h2><span class="muted" id="todayDate"></span></div><div id="todayTasks"></div>
 <div class="actions"><button class="btn" onclick="showTab('quests')">＋ ساخت مأموریت</button><button class="btn secondary" onclick="dailyReset()">روز جدید</button></div>
</section>
<section id="quests" class="panel hidden">
 <div class="sectionhead"><h2>📜 مدیریت مأموریت‌ها</h2><span class="muted">روزانه و هفتگی</span></div>
 <div class="card"><div class="formgrid">
 <div class="field full"><label>نام مأموریت</label><input id="qName" placeholder="مثلاً ۴۵ دقیقه تمرین تتو"></div>
 <div class="field"><label>شاخه</label><select id="qSkill"><option value="tattoo">تتو</option><option value="business">بیزینس</option><option value="fitness">فیتنس</option><option value="discipline">نظم شخصی</option></select></div>
 <div class="field"><label>نوع</label><select id="qType"><option value="daily">روزانه</option><option value="weekly">هفتگی</option><option value="once">یک‌باره</option></select></div>
 <div class="field"><label>XP پاداش</label><input id="qXp" type="number" min="1" max="500" value="25"></div>
 <div class="field"><label>سختی</label><select id="qDiff"><option>آسان</option><option selected>متوسط</option><option>سخت</option><option>باس</option></select></div>
 </div><div class="actions"><button class="btn" onclick="addQuest()">افزودن مأموریت</button></div></div><div id="questList"></div>
</section>
<section id="tree" class="panel hidden">
 <div class="sectionhead"><h2>🌳 درخت مهارت تتو</h2><span class="muted">با XP تتو باز می‌شود</span></div><div id="treeNodes"></div>
 <div class="sectionhead"><h2>🏢 مسیر بیزینس</h2></div><div id="businessNodes"></div>
 <div class="sectionhead"><h2>💪 مسیر فیتنس</h2></div><div id="fitnessNodes"></div>
</section>
<section id="rewards" class="panel hidden">
 <div class="sectionhead"><h2>🎁 فروشگاه پاداش</h2><span class="muted">XP خرج کن، جایزه بگیر</span></div>
 <div class="card"><div class="formgrid"><div class="field full"><label>نام پاداش</label><input id="rName" placeholder="مثلاً یک فیلم و استراحت"></div><div class="field"><label>هزینه XP</label><input id="rCost" type="number" value="100" min="1"></div></div><div class="actions"><button class="btn" onclick="addReward()">افزودن پاداش</button></div></div><div id="rewardList"></div>
</section>
<section id="report" class="panel hidden">
 <div class="sectionhead"><h2>📊 گزارش هفتگی</h2><span class="muted" id="weekRange"></span></div><div class="stats"><div class="stat"><b id="doneWeek">۰</b><span>مأموریت تکمیل‌شده</span></div><div class="stat"><b id="xpWeek">۰</b><span>XP کسب‌شده</span></div><div class="stat"><b id="rateWeek">۰٪</b><span>نرخ انجام</span></div></div><div id="reportSkills" style="margin-top:14px"></div>
 <div class="card"><label class="muted">یادداشت پایان هفته</label><textarea id="weeklyNote" rows="3" placeholder="چه چیزی خوب پیش رفت؟ کجا عقب افتادی؟"></textarea><div class="actions"><button class="btn" onclick="saveNote()">ذخیره گزارش</button></div></div>
</section>
<section id="settings" class="panel hidden">
 <div class="sectionhead"><h2>⚙️ تنظیمات و اطلاعات</h2></div><div class="card"><p class="muted">اطلاعات در حافظه همین مرورگر ذخیره می‌شود. برای انتقال به گوشی یا مرورگر دیگر، فایل پشتیبان بگیر.</p><div class="actions"><button class="btn green" onclick="exportData()">⬇ خروجی پشتیبان</button><label class="btn secondary">⬆ بازیابی پشتیبان<input type="file" accept="application/json" onchange="importData(event)" hidden></label><button class="btn danger" onclick="resetAll()">پاک‌کردن همه اطلاعات</button></div></div><div class="card"><b>قوانین سیستم</b><p class="muted">هر ۱۰۰ XP = یک لول. تکمیل مأموریت فقط یک‌بار در هر بازه پاداش XP می‌دهد. روز جدید، مأموریت‌های روزانه را دوباره فعال می‌کند؛ سابقه قبلی حفظ می‌شود.</p><div class="field"><label>نام بازیکن (اختیاری)</label><input id="playerName" placeholder="بازیکن"></div><div class="actions"><button class="btn" onclick="saveName()">ذخیره نام</button></div></div>
</section>
<div class="footer">LIFE RPG · نسخه شخصی آفلاین · داده‌ها روی همین دستگاه ذخیره می‌شوند</div>
</main><div class="toast" id="toast"></div>
<script>
const KEY='life_rpg_fa_v1';
const defaults={
 xp:0,spent:0,created:new Date().toISOString(),lastDay:'',history:[],name:'',
 skills:{tattoo:0,business:0,fitness:0,discipline:0},
 quests:[
 {id:1,name:'۴۵ دقیقه تمرین تتو',skill:'tattoo',type:'daily',xp:30,diff:'متوسط',done:[]},
 {id:2,name:'یک جلسه کار متمرکز روی بیزینس',skill:'business',type:'daily',xp:30,diff:'متوسط',done:[]},
 {id:3,name:'انجام تمرین باشگاه',skill:'fitness',type:'daily',xp:25,diff:'متوسط',done:[]},
 {id:4,name:'ثبت گزارش پایان روز',skill:'discipline',type:'daily',xp:10,diff:'آسان',done:[]},
 {id:5,name:'تکمیل یک طرح یا تمرین جدی تتو',skill:'tattoo',type:'weekly',xp:80,diff:'سخت',done:[]},
 {id:6,name:'مرور فروش و عملکرد بیزینس',skill:'business',type:'weekly',xp:50,diff:'متوسط',done:[]}
 ],
 rewards:[{id:1,name:'یک فیلم بدون عذاب وجدان',cost:100},{id:2,name:'خرید کوچک دلخواه',cost:300},{id:3,name:'نیم‌روز استراحت کامل',cost:450}],
 notes:{},log:[]
};
let state=load();
function load(){try{return {...structuredClone(defaults),...JSON.parse(localStorage.getItem(KEY)||'{}')};}catch(e){return structuredClone(defaults)}}
function save(){localStorage.setItem(KEY,JSON.stringify(state));render()}
function day(){return new Date().toISOString().slice(0,10)}
function weekStart(d=new Date()){let x=new Date(d);x.setHours(0,0,0,0);x.setDate(x.getDate()-((x.getDay()+6)%7));return x.toISOString().slice(0,10)}
function fa(n){return Number(n||0).toLocaleString('fa-IR')}
function skillName(k){return {tattoo:'تتو',business:'بیزینس',fitness:'فیتنس',discipline:'نظم شخصی'}[k]||k}
function skillLevel(x){return Math.floor(x/100)+1}
function notify(t){let el=document.getElementById('toast');el.textContent=t;el.style.display='block';setTimeout(()=>el.style.display='none',2100)}
function gain(q){let d=day();if(q.done.includes(d)){notify('این مأموریت امروز قبلاً ثبت شده');return}q.done.push(d);state.xp+=q.xp;state.skills[q.skill]=(state.skills[q.skill]||0)+q.xp;state.log.push({date:d,xp:q.xp,skill:q.skill,quest:q.name});save();notify('آفرین! '+fa(q.xp)+' XP دریافت کردی')}
function uncomplete(q){let d=day();if(!q.done.includes(d))return;q.done=q.done.filter(x=>x!==d);state.xp=Math.max(0,state.xp-q.xp);state.skills[q.skill]=Math.max(0,(state.skills[q.skill]||0)-q.xp);state.log=state.log.filter(x=>!(x.date===d&&x.quest===q.name));save()}
function addQuest(){let name=document.getElementById('qName').value.trim();if(!name){notify('نام مأموریت را وارد کن');return}state.quests.push({id:Date.now(),name,skill:document.getElementById('qSkill').value,type:document.getElementById('qType').value,xp:Math.max(1,+document.getElementById('qXp').value||25),diff:document.getElementById('qDiff').value,done:[]});document.getElementById('qName').value='';save();notify('مأموریت اضافه شد')}
function delQuest(id){if(confirm('این مأموریت حذف شود؟')){state.quests=state.quests.filter(q=>q.id!==id);save()}}
function addReward(){let name=document.getElementById('rName').value.trim(),cost=+document.getElementById('rCost').value;if(!name||cost<1)return notify('نام و هزینه معتبر وارد کن');state.rewards.push({id:Date.now(),name,cost});document.getElementById('rName').value='';save()}
function buy(id){let r=state.rewards.find(x=>x.id===id);if(!r)return;if(state.xp-state.spent<r.cost)return notify('XP کافی نداری');if(confirm(`پاداش «${r.name}» با ${fa(r.cost)} XP خریداری شود؟`)){state.spent+=r.cost;state.log.push({date:day(),xp:0,spent:r.cost,quest:'خرید: '+r.name});save();notify('پاداش خریداری شد')}}
function dailyReset(){if(!confirm('روز جدید شروع شود؟ مأموریت‌های روزانه دوباره فعال می‌شوند.'))return;state.lastDay=day();save();notify('آماده شروع روز تازه‌ای')}
function showTab(t){document.querySelectorAll('.panel').forEach(x=>x.classList.add('hidden'));document.getElementById(t).classList.remove('hidden');document.querySelectorAll('.tab').forEach(x=>x.classList.toggle('active',x.dataset.tab===t));if(t==='report')renderReport();if(t==='tree')renderTree();if(t==='quests')renderQuests();if(t==='rewards')renderRewards()}
document.querySelectorAll('.tab').forEach(b=>b.addEventListener('click',()=>showTab(b.dataset.tab)));
function render(){let level=Math.floor(state.xp/100)+1,into=state.xp%100;document.getElementById('level').textContent='LV. '+fa(level);document.getElementById('totalXp').textContent=fa(state.xp)+' XP کل · '+fa(state.xp-state.spent)+' XP قابل‌خرج';document.getElementById('rank').textContent=level<3?'تازه‌وارد':level<6?'ماجراجو':level<10?'متخصص':'افسانه‌ای';document.getElementById('levelBar').style.width=into+'%';document.getElementById('levelProgress').textContent=fa(into)+' / ۱۰۰ XP تا لول بعد';
let today=day(),w=weekStart();let todays=state.quests.filter(q=>q.type==='daily'||q.type==='once'&&!q.done.length);document.getElementById('todayCount').textContent=fa(todays.filter(q=>q.done.includes(today)).length+'/'+todays.length);document.getElementById('weekXp').textContent=fa(state.log.filter(x=>x.date>=w).reduce((a,x)=>a+(x.xp||0),0));
let days=[...new Set(state.log.map(x=>x.date))].sort();let streak=0;for(let i=0;i<365;i++){let d=new Date();d.setDate(d.getDate()-i);if(days.includes(d.toISOString().slice(0,10)))streak++;else if(i>0)break}document.getElementById('streak').textContent=fa(streak);
document.getElementById('dateLabel').textContent='فصل اول · '+(state.name||'بازیکن');document.getElementById('todayDate').textContent=new Date().toLocaleDateString('fa-IR',{weekday:'long',month:'long',day:'numeric'});
let skills=[['tattoo','🎨','#a78bfa'],['business','💼','#60a5fa'],['fitness','💪','#34d399']];document.getElementById('skills').innerHTML=skills.map(([k,e,c])=>{let x=state.skills[k]||0,l=skillLevel(x);return `<div class="skill" style="--c:${c}"><div class="emoji">${e}</div><strong>${skillName(k)}</strong><small>LV ${fa(l)} · ${fa(x)} XP</small><div class="bar"><i style="width:${x%100}%"></i></div></div>`}).join('');
document.getElementById('todayTasks').innerHTML=todays.length?todays.map(q=>taskHTML(q,today)).join(''):'<div class="empty">هنوز مأموریتی تعریف نشده.</div>';renderQuests();renderRewards();document.getElementById('playerName').value=state.name||''}
function taskHTML(q,d){let done=q.done.includes(d);return `<div class="task ${done?'done':''}"><input type="checkbox" ${done?'checked':''} onchange="${done?`uncompleteById(${q.id})`:`completeById(${q.id})`}"><div class="taskmain"><div class="taskname">${esc(q.name)}</div><div class="taskmeta">${skillName(q.skill)} · ${q.type==='daily'?'روزانه':q.type==='weekly'?'هفتگی':'یک‌باره'} · ${fa(q.xp)} XP · ${q.diff}</div></div><span class="tag">${done?'انجام شد':'+'+fa(q.xp)+' XP'}</span></div>`}
function completeById(id){let q=state.quests.find(x=>x.id===id);if(q)gain(q)}
function uncompleteById(id){let q=state.quests.find(x=>x.id===id);if(q)uncomplete(q)}
function renderQuests(){let el=document.getElementById('questList');if(!el)return;el.innerHTML=state.quests.map(q=>`<div class="listrow"><div><b>${esc(q.name)}</b><div class="taskmeta">${skillName(q.skill)} · ${q.type==='daily'?'روزانه':q.type==='weekly'?'هفتگی':'یک‌باره'} · ${fa(q.xp)} XP</div></div><button class="btn danger" onclick="delQuest(${q.id})">حذف</button></div>`).join('')}
const trees={tree:[['کنترل دست و خط','Line Control',0],['کنترل سایه‌زنی','Shading Mastery',100],['رئالیسم پایه','Realism Foundations',250],['مطالعه آثار کلاسیک','Classical Art',500],['اجرای حرفه‌ای','Professional Artist',900]],business:[['نظم فروش و پشتیبانی','Sales System',0],['تحلیل داده و مشتری','Customer Analytics',150],['ساخت سیستم رشد','Growth Engine',400],['برند مستقل','Independent Brand',800]],fitness:[['ثبات تمرین','Consistency',0],['تغذیه و ریکاوری','Nutrition & Recovery',150],['قدرت و عضله‌سازی','Strength Builder',400],['بدن هدف','Peak Form',800]]};
function renderTree(){let keys=[['tattoo','treeNodes'],['business','businessNodes'],['fitness','fitnessNodes']];keys.forEach(([k,id])=>{let x=state.skills[k]||0;document.getElementById(id).innerHTML=trees[k==='tattoo'?'tree':k].map((n,i)=>`<div class="node ${x>=n[2]?'unlocked':''}"><b>${x>=n[2]?'🔓':'🔒'} ${n[0]}</b><small>${n[1]} · نیازمند ${fa(n[2])} XP ${x>=n[2]?'· باز شده':''}</small></div>`).join('')})}
function renderRewards(){document.getElementById('rewardList').innerHTML=state.rewards.map(r=>`<div class="listrow"><div><b>🎁 ${esc(r.name)}</b><div class="taskmeta">${fa(r.cost)} XP</div></div><button class="btn ${state.xp-state.spent>=r.cost?'green':'secondary'}" onclick="buy(${r.id})">خرید</button></div>`).join('')}
function renderReport(){let w=weekStart(),logs=state.log.filter(x=>x.date>=w),xp=logs.reduce((a,x)=>a+(x.xp||0),0),done=logs.filter(x=>x.xp>0).length,all=state.quests.filter(q=>q.type!=='once'||!q.done.length).length*7;document.getElementById('doneWeek').textContent=fa(done);document.getElementById('xpWeek').textContent=fa(xp);document.getElementById('rateWeek').textContent=fa(Math.min(100,Math.round(done/Math.max(1,all)*100)))+'٪';document.getElementById('weekRange').textContent='از '+new Date(w).toLocaleDateString('fa-IR');document.getElementById('reportSkills').innerHTML=['tattoo','business','fitness','discipline'].map(k=>`<div class="listrow"><b>${skillName(k)}</b><span>${fa(logs.filter(x=>x.skill===k).reduce((a,x)=>a+(x.xp||0),0))} XP</span></div>`).join('');document.getElementById('weeklyNote').value=state.notes[w]||''}
function saveNote(){state.notes[weekStart()]=document.getElementById('weeklyNote').value;save();notify('گزارش ذخیره شد')}
function saveName(){state.name=document.getElementById('playerName').value.trim();save();notify('ذخیره شد')}
function exportData(){let b=new Blob([JSON.stringify(state,null,2)],{type:'application/json'}),a=document.createElement('a');a.href=URL.createObjectURL(b);a.download='life-rpg-backup.json';a.click();URL.revokeObjectURL(a.href)}
function importData(e){let f=e.target.files[0];if(!f)return;let r=new FileReader();r.onload=()=>{try{let x=JSON.parse(r.result);if(!x.quests||!x.skills)throw 0;state={...structuredClone(defaults),...x};save();notify('پشتیبان بازیابی شد')}catch(_){notify('فایل پشتیبان معتبر نیست')}};r.readAsText(f)}
function resetAll(){if(confirm('تمام XP، مأموریت‌ها و سابقه برای همیشه پاک شود؟')){localStorage.removeItem(KEY);state=structuredClone(defaults);save();notify('اطلاعات بازنشانی شد')}}
function esc(s){return String(s).replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]))}
render();
</script></body></html>
<head>
<link rel="icon" type="image/png" href="./icon.png">
<link rel="apple-touch-icon" href="./icon.png">
