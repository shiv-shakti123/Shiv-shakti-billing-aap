<script>
function chg1(v){let e=document.getElementById('q1');e.value=Math.max(0,parseInt(e.value||0)+v);upd()}
function chg2(v){let e=document.getElementById('q2');e.value=Math.max(0,parseInt(e.value||0)+v);upd()}
function upd(){
let q1=parseInt(document.getElementById('q1').value||0);
let q2=parseInt(document.getElementById('q2').value||0);
let t1=q1*200,t2=q2*1000,tt=t1+t2;
document.getElementById('t').innerText='₹'+tt;
document.getElementById('d').innerText=new Date().toLocaleDateString('en-IN');
document.getElementById('bc').innerText=document.getElementById('cname').value;
document.getElementById('bm').innerText=document.getElementById('cmob').value;
document.getElementById('bq1').innerText=q1;document.getElementById('bt1').innerText=t1;
document.getElementById('bq2').innerText=q2;document.getElementById('bt2').innerText=t2;
document.getElementById('bt').innerText=tt;
}
document.getElementById('q1').oninput=upd;document.getElementById('q2').oninput=upd;
document.getElementById('cname').oninput=upd;document.getElementById('cmob').oninput=upd;
upd();
</script>
