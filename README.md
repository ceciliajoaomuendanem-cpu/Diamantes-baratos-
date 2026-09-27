<!DOCTYPE html>
<html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>DIAMANTES BARATOS MZ</title>
<style>*{margin:0;padding:0;box-sizing:border-box;font-family:Arial}body{background:#0f0f0f;color:white}.header{background:linear-gradient(135deg,#ff0040,#cc0000);padding:20px;text-align:center}.banner{background:#00ff88;color:#000;text-align:center;padding:8px;font-weight:900;font-size:13px}.container{padding:12px;max-width:600px;margin:auto}.grid{display:grid;grid-template-columns:1fr 1fr;gap:10px}.card{background:#1e1e28;border-radius:14px;padding:14px;text-align:center;border:1px solid #2a2a3a;cursor:pointer}.card:active{transform:scale(0.95)}.card .price{color:#00ff88;font-weight:900;font-size:20px;margin-top:6px}.modal{display:none;position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,0.9);z-index:100;justify-content:center;align-items:center;padding:15px}.modal.ativo{display:flex}.box{background:#1e1e28;width:100%;max-width:380px;border-radius:16px;padding:20px;border:2px solid #00ff88}.box input,.box select{width:100%;padding:12px;border-radius:8px;border:none;margin:8px 0;background:#2a2a3a;color:white}.btn{background:#25D366;color:white;padding:14px;border:none;border-radius:10px;width:100%;font-weight:900;margin-top:10px;cursor:pointer}.btn2{background:#333;color:white;padding:10px;border:none;border-radius:10px;width:100%;margin-top:8px}.pag{background:#1a1a2e;border:2px solid #00ff88;border-radius:14px;padding:16px;text-align:center;margin-top:20px}</style></head><body>
<div class="header"><h1>DIAMANTES BARATOS MZ</h1><p>Compra 100% dentro do App - Entrega 2-10min</p></div>
<div class="banner">CLICA NO PACOTE E PAGA DENTRO DO APP</div>
<div class="container">
<div class="grid">
<div class="card" onclick="comprar('110 Diamantes','95 MT')">110D<div class="price">95 MT</div></div>
<div class="card" onclick="comprar('231 Diamantes','180 MT')">231D<div class="price">180 MT</div></div>
<div class="card" onclick="comprar('341 Diamantes','265 MT')">341D<div class="price">265 MT</div></div>
<div class="card" onclick="comprar('462 Diamantes','340 MT')">462D<div class="price">340 MT</div></div>
<div class="card" onclick="comprar('583 Diamantes','440 MT')">583D<div class="price">440 MT</div></div>
<div class="card" onclick="comprar('693 Diamantes','500 MT')">693D<div class="price">500 MT</div></div>
<div class="card" onclick="comprar('814 Diamantes','575 MT')">814D<div class="price">575 MT</div></div>
<div class="card" onclick="comprar('1188 Diamantes','835 MT')">1188D<div class="price">835 MT</div></div>
<div class="card" onclick="comprar('1419 Diamantes','995 MT')">1419D<div class="price">995 MT</div></div>
<div class="card" onclick="comprar('1771 Diamantes','1259 MT')">1771D<div class="price">1259 MT</div></div>
<div class="card" onclick="comprar('2420 Diamantes','1580 MT')">2420D<div class="price">1580 MT</div></div>
<div class="card" onclick="comprar('3003 Diamantes','1990 MT')">3003D<div class="price">1990 MT</div></div>
<div class="card" onclick="comprar('3608 Diamantes','2365 MT')">3608D<div class="price">2365 MT</div></div>
<div class="card" onclick="comprar('4191 Diamantes','2780 MT')">4191D<div class="price">2780 MT</div></div>
<div class="card" onclick="comprar('Semanal 450D','195 MT')">Semanal 450D<div class="price">195 MT</div></div>
<div class="card" onclick="comprar('Mensal 2600D','880 MT')">Mensal 2600D<div class="price">880 MT</div></div>
<div class="card" onclick="comprar('Passe 6-15 520D','220 MT')">Passe 6-15<div class="price">220 MT</div></div>
<div class="card" onclick="comprar('Passe 20-30 750D','260 MT')">Passe 20-30<div class="price">260 MT</div></div>
</div>
<div class="pag"><b>Formas de Pagamento dentro do App</b><br><br>M-Pesa / e-Mola<br><b>843375877 Ramadam</b><br><b>865646849 Horacio</b></div>
</div>
<div class="modal" id="modal"><div class="box">
<h2 id="titulo" style="color:#00ff88;text-align:center"></h2>
<p id="preco" style="text-align:center;font-size:22px;font-weight:900;margin:10px 0"></p>
<input type="text" id="idff" placeholder="Seu ID do Free Fire">
<select id="pag"><option>M-Pesa 843375877 Ramadam</option><option>e-Mola 865646849 Horacio</option></select>
<div id="instru" style="background:#2a2a3a;padding:10px;border-radius:8px;margin:10px 0;font-size:13px;text-align:center">1. Pague para o numero escolhido<br>2. Envie comprovativo<br>3. Entrega em 2-10min via ID</div>
<button class="btn" onclick="finalizar()">JA PAGUEI - ENVIAR COMPROVATIVO</button>
<button class="btn2" onclick="fechar()">Cancelar</button>
</div></div>
<script>
let pacoteAtual='', precoAtual='';
function comprar(pacote,preco){pacoteAtual=pacote;precoAtual=preco;document.getElementById('titulo').innerText=pacote;document.getElementById('preco').innerText=preco;document.getElementById('modal').classList.add('ativo')}
function fechar(){document.getElementById('modal').classList.remove('ativo')}
function finalizar(){let id=document.getElementById('idff').value;let pag=document.getElementById('pag').value;if(id==''){alert('Coloca seu ID do Free Fire!');return}let msg=`Ola! Comprei dentro do App%0A%0APacote: ${pacoteAtual}%0APreco: ${precoAtual}%0AID: ${id}%0APagamento: ${pag}%0A%0AJa paguei, segue comprovativo:`;window.open(`https://wa.me/258848746485?text=${msg}`,'_blank');fechar()}
</script></body></html>
