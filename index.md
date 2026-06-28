---
layout: default
title: "Previa Cumpleaños! 🎉"
---

<div class="terminal-bg">
  <div class="terminal-header">
    <span class="term-dot red"></span>
    <span class="term-dot yellow"></span>
    <span class="term-dot green"></span>
    <span class="term-title">rodixxi@bday:~$</span>
  </div>
  <div class="tab-bar">
    <a class="tab active" href="#invitacion">🎉</a>
    <a class="tab" href="#detalles">📋</a>
    <a class="tab" href="#mapa">🗺️</a>
    <a class="tab" href="#confirmar">✅</a>
    <a class="tab" href="#regalos">🎁</a>
    <a class="tab" href="#mensaje-final">💬</a>
    <a class="tab" href="#clima">☀️</a>
  </div>
  <div class="terminal-content">
    <div class="card-row">
      <div class="card card-pink" id="invitacion">
        <div class="card-title">Invitación</div>
        <div class="card-body">
          <span class="term-prompt">$ cat invitacion.txt</span>
          <div class="term-block">
            Te invito a celebrar la previa a mi cumple, que es el 7. ¡La previa es antes, el 5!<br>
          </div>
        </div>
      </div>
      <div class="card card-blue" id="detalles">
        <div class="card-title">Detalles</div>
        <div class="card-body">
          <span class="term-prompt">$ cat detalles.txt</span>
          <div class="term-block">
            <b>Fecha y Hora:</b> Domingo 5 de Julio al mediodía (pero podés llegar antes para ayudar y aprovechar el solsito)<br>
            <b>Ubicación:</b> Villa Santa Rosa, Córdoba<br>
            <b>Requisito:</b> Trae lo que vallas a tomar y vajilla, la carne la pongo yo.<br>
            <b>Nota:</b> Esto es la previa, el cumpleaños es el martes 7
          </div>
        </div>
      </div>
    </div>
    <div class="card-row">
      <div class="card card-green" id="mapa">
        <div class="card-title">Mapa</div>
        <div class="card-body">
          <span class="term-prompt">$ cat ubicacion.txt</span>
          <div class="map-container">
            <iframe 
              src="https://www.google.com/maps/embed?pb=!1m17!1m12!1m3!1d3414.653405183036!2d-63.41376932362741!3d-31.14713887438699!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m2!1m1!2zMzHCsDA4JzQ5LjciUyA2M8KwMjQnNDAuMyJX!5e0!3m2!1ses-419!2sus!4v1751393728859!5m2!1ses-419!2sus"
              width="100%" 
              height="200" 
              style="border:0;" 
              allowfullscreen="" 
              loading="lazy" 
              referrerpolicy="no-referrer-when-downgrade">
            </iframe>
            <div class="map-info">
              <span class="term-green">Ubicación Exacta:</span> 31°08'49.7"S 63°24'40.3"W
            </div>
          </div>
        </div>
      </div>
      <div class="card card-yellow" id="confirmar">
        <div class="card-title">Confirmar</div>
        <div class="card-body">
          <span class="term-prompt">$ sh</span>
          <a href="https://forms.gle/sENKidqqTvpMPL4s8" class="term-btn" target="_blank">./confirmar_asistencia.sh</a>
        </div>
      </div>
    </div>
    <div class="card-row">
      <div class="card card-purple" id="regalos">
        <div class="card-title">Regalos</div>
        <div class="card-body">
          <span class="term-prompt">$ cat regalos.txt</span>
          <div class="term-block">
            Tu presencia es el mejor regalo... mentira...<br>
            Se aceptan transferencias a mi alias <span class="term-green">rodrigocrespillo.mp</span> o activo el ramsonware en tu pc
          </div>
        </div>
      </div>
      <div class="card card-cyan" id="mensaje-final">
        <div class="card-title">Mensaje Final</div>
        <div class="card-body">
          <span class="term-prompt">$ echo "Nos re vimos pa!"</span>
          <div class="term-block term-green">"EEEAAAA!!!!"</div>
        </div>
      </div>
    </div>
    <div class="card-row">
      <div class="card card-grey" id="clima">
        <div class="card-title">Clima (Ahora)</div>
        <div class="card-body">
          <span class="term-prompt">$ curl wttr.in/-31.1506846,-63.4220181?1 # clima estimado para el Domingo 5 de Julio</span>
          <div class="term-block" style="background:#d9d9d9; color:#b6ffb0;">
            <iframe src="https://wttr.in/-31.1506846,-63.4220181?1" width="100%" height="180" style="background:#d9d9d9; color:#b6ffb0; border:none; overflow:hidden;"></iframe>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="status-bar">
    <span class="status-label">STATUS</span> <span class="status-value">Ready to party</span>
    <span class="status-right">UTF-8 <span class="status-emoji">🎂</span></span>
  </div>
</div>

<style>
body {
  background: #181c1f;
}
.terminal-bg {
  background: #181c1f;
  color: #b6ffb0;
  font-family: 'Fira Mono', 'Consolas', 'Menlo', 'Monaco', 'Liberation Mono', monospace;
  max-width: 1100px;
  margin: 40px auto 0 auto;
  border-radius: 16px;
  box-shadow: 0 0 50px #000c, 0 0 0 1px #00ff0022;
  border: 2px solid #222;
  overflow: hidden;
}
.terminal-header {
  background: #23272a;
  padding: 0.7em 1em;
  display: flex;
  align-items: center;
  border-bottom: 2px solid #222;
}
.term-dot {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  display: inline-block;
  margin-right: 7px;
}
.term-dot.red { background: #ff5f56; }
.term-dot.yellow { background: #ffbd2e; }
.term-dot.green { background: #27c93f; }
.term-title {
  color: #b6ffb0;
  font-weight: bold;
  margin-left: 1em;
  font-size: 1.1em;
  letter-spacing: 1px;
}
.tab-bar {
  background: #191c1f;
  border-bottom: 2px solid #23272a;
  display: flex;
  gap: 1.5em;
  padding: 0.7em 2em 0.7em 2em;
}
.tab {
  color: #b6ffb0;
  background: transparent;
  border: 2px solid #23272a;
  border-bottom: none;
  border-radius: 10px 10px 0 0;
  padding: 0.4em 1.5em;
  font-weight: bold;
  font-size: 1em;
  margin-right: 0.5em;
  cursor: pointer;
  transition: background 0.2s, color 0.2s, transform 0.15s;
}
.tab:hover {
  transform: translateY(-2px);
}
.tab.active {
  background: #23272a;
  color: #fff;
  border-bottom: 2px solid #181c1f;
}
.terminal-content {
  padding: 2em 2em 2.5em 2em;
}
.card-row {
  display: flex;
  gap: 2em;
  margin-bottom: 2em;
  flex-wrap: wrap;
}
.card {
  flex: 1 1 350px;
  min-width: 320px;
  background: #23272a;
  border-radius: 14px;
  box-shadow: 0 2px 12px #0002;
  border: 2.5px solid #23272a;
  margin-bottom: 1em;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 20px #0006;
}
.card-title {
  font-size: 1.1em;
  font-weight: bold;
  padding: 1em 1.5em 0.5em 1.5em;
  color: #fff;
  letter-spacing: 1px;
}
.card-body {
  padding: 0 1.5em 1.5em 1.5em;
}
.card-pink {
  border-color: #ff7edb;
  background: linear-gradient(135deg, #2a1a2e 60%, #ff7edb22 100%);
}
.card-blue {
  border-color: #7edbff;
  background: linear-gradient(135deg, #1a232e 60%, #7edbff22 100%);
}
.card-green {
  border-color: #7effb0;
  background: linear-gradient(135deg, #1a2e23 60%, #7effb022 100%);
}
.card-yellow {
  border-color: #ffe97e;
  background: linear-gradient(135deg, #2e2c1a 60%, #ffe97e22 100%);
}
.card-purple {
  border-color: #a97eff;
  background: linear-gradient(135deg, #231a2e 60%, #a97eff22 100%);
}
.card-cyan {
  border-color: #7efff7;
  background: linear-gradient(135deg, #1a2e2e 60%, #7efff722 100%);
}
.term-prompt {
  color: #00ff00;
  margin: 1.2em 0 0.2em 0;
  font-size: 1em;
  font-family: inherit;
}
.term-block {
  background: #23272a;
  color: #b6ffb0;
  padding: 1em 1.5em;
  border-radius: 6px;
  margin-bottom: 1.2em;
  font-size: 1em;
  font-family: inherit;
  white-space: pre-line;
}
.term-green {
  color: #00ff00;
}
.term-btn {
  display: inline-block;
  background: #23272a;
  color: #00ff00;
  border: 1.5px solid #00ff00;
  border-radius: 4px;
  padding: 0.7em 2em;
  font-family: inherit;
  font-size: 1em;
  margin: 1em 0 2em 0;
  text-decoration: none;
  font-weight: bold;
  transition: background 0.2s, color 0.2s;
}
.term-btn:hover {
  background: #00ff00;
  color: #181c1f;
}
.gift-list {
  color: #ffe97e;
  font-weight: bold;
  font-size: 1.1em;
  letter-spacing: 1px;
}
.map-container {
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  margin: 1.5em 0;
  border: 1px solid #222;
}
.map-info {
  background: #111;
  padding: 1rem;
  text-align: center;
  border-top: 1px solid #222;
  color: #b6ffb0;
}
.status-bar {
  background: #23272a;
  color: #fff;
  font-family: inherit;
  font-size: 1em;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0.7em 2em;
  border-top: 2px solid #222;
}
.status-label {
  background: #ff5f56;
  color: #fff;
  padding: 0.2em 0.8em;
  border-radius: 4px;
  font-weight: bold;
  margin-right: 0.7em;
}
.status-value {
  color: #b6ffb0;
  font-weight: bold;
}
.status-right {
  color: #ffe97e;
  font-weight: bold;
  font-size: 1em;
  display: flex;
  align-items: center;
  gap: 0.5em;
}
.status-emoji {
  font-size: 1.2em;
}
@media (max-width: 900px) {
  .card-row {
    flex-direction: column;
    gap: 1em;
  }
  .terminal-content {
    padding: 1em 0.5em 1.5em 0.5em;
  }
}
@media (max-width: 600px) {
  .terminal-bg {
    max-width: 99vw;
  }
  .card {
    min-width: 90vw;
  }
}
</style> 