<!DOCTYPE html>
<html><head><meta name="viewport" content="width=device-width,initial-scale=1">
<title>Shiv Shakti Billing</title>
<style>
body{font-family:Arial;background:#f2f2f2;margin:0}
.h{background:#ff6f00;color:#fff;padding:15px;text-align:center;font-weight:bold;font-size:20px}
.box{background:#fff;margin:10px;padding:15px;border-radius:10px}
input{width:100%;padding:12px;margin:6px 0;border:1px solid #ccc;border-radius:8px;box-sizing:border-box}
button{background:#ff6f00;color:#fff;border:0;padding:12px;width:100%;border-radius:8px;font-weight:bold;margin-top:8px}
table{width:100%;margin-top:10px;border-collapse:collapse}
td,th{border:1px solid #ddd;padding:6px;text-align:center}
@media print{body *{visibility:hidden}.print-area, .print-area *{visibility:visible}.print-area{position:absolute;left:0;top:0;width:100%}}
</style></head><body>
<div class="h">🔱 Shiv Shakti Billing App</div>

<div class="box">
<h3>Client Details</h3>
<input id="cname" placeholder="Client ka Naam">
<input id="cmob" placeholder="Mobile Number">
</div>

<div class="box">
<h3>Item Add Karo</h3>
<input id="iname" placeholder="Item Name">
<input id="qty" type="number" placeholder="Quantity">
<input id="price" type="number" placeholder="Price per piece">
<button onclick="addItem()">+ Item Jodo</button>
<table id="tbl"><tr style="background:#ff6f00;color:#fff"><th>Item</th><th>Qty</th><th>Price</th><th>Total</th></tr></table>
<h3 id="total">Total: Rs 0</h3>
</div>

<div class="box print-area" id="billArea" style="display:none">
<h2 style="text-align:center">Shiv Shakti</h2>
<p id="bclient"></p>
<div id="bitems"></div>
<h3 id="btotal"></h3>
<p style="text-align:center">Thank You!</p>
</div>

<div style="margin:10px">
<button onclick="makeBill()">Bill Banao / Print Karo</button>
<button onclick="location.reload()" style="background:#333">Naya Bill</button>
</div>

<script>
let items=[], total=0;
function addItem(){
 let n=iname.value, q=Number(qty.value), p=Number(price.value);
 if(!n||!q||!p){alert("Sab bharo");return}
 let t=q*p; items.push({n,q,p,t}); total+=t;
 tbl.innerHTML+=`<tr><td>${n}</td><td>${q}</td><td>${p}</td><td>${t}</td></tr>`;
 document.getElementById("total").innerText="Total: Rs "+total;
 iname.value="";qty.value="";price.value="";
}
function makeBill(){
 if(items.length==0){alert("Pehle item jodo");return}
 bclient.innerText="Client: "+cname.value+" | Mob: "+cmob.value;
 let h='<table><tr><th>Item</th><th>Qty</th><th>Total</th></tr>';
 items.forEach(i=>{h+=`<tr><td>${i.n}</td><td>${i.q}</td><td>${i.t}</td></tr>`});
 h+='</table>'; bitems.innerHTML=h;
 btotal.innerText="Total: Rs "+total;
 billArea.style.display="block";
 setTimeout(()=>{window.print(); billArea.style.display="none"},500);
}
</script></body></html>
