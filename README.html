<!doctype html>
<html lang="pl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Protokół przeglądu instalacji elektrycznej — formularz</title>
  <style>
    :root{--bg:#f6f8fb;--card:#fff;--accent:#1f6feb;--muted:#6b7280}
    body{font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; background:var(--bg); margin:0; padding:24px}
    .container{max-width:980px;margin:0 auto}
    header{display:flex;justify-content:space-between;align-items:center;margin-bottom:16px}
    h1{font-size:20px;margin:0}
    .card{background:var(--card);border-radius:10px;padding:16px;box-shadow:0 6px 18px rgba(20,20,40,0.06);margin-bottom:16px}
    label{display:block;font-size:13px;color:var(--muted);margin-bottom:6px}
    input[type=text], input[type=number], select, textarea{width:100%;padding:8px;border:1px solid #e5e7eb;border-radius:6px;font-size:14px}
    .row{display:flex;gap:12px}
    .col{flex:1}
    .muted{color:var(--muted);font-size:13px}
    button{background:var(--accent);color:#fff;border:none;padding:8px 12px;border-radius:8px;cursor:pointer}
    button.ghost{background:transparent;color:var(--accent);border:1px solid #dbeafe}
    table{width:100%;border-collapse:collapse;margin-top:8px}
    th,td{border:1px solid #eef2f7;padding:8px;text-align:left;font-size:14px}
    th{background:#fbfdff}
    @media (max-width:720px){.row{flex-direction:column}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Protokół przeglądu instalacji elektrycznej — formularz</h1>
    </header>

    <form id="protocolForm" class="card" onsubmit="return handleSubmit(event)">
      <!-- Dane lokalowe -->
      <section>
        <h2 style="margin:0 0 8px 0;font-size:16px">Dane lokalowe</h2>
        <div class="row">
          <div class="col">
            <label>Lokal / data</label>
            <input type="text" id="protocolNumber" placeholder="format - 1/28/10/2025" />
          </div>
          <div class="col">
            <label>Zleceniodawca / Administracja</label>
            <input type="text" id="client" placeholder="Nazwa zleceniodawcy" />
          </div>
        </div>
        <div style="margin-top:12px" class="row">
          <div class="col">
            <label>Adres budynku</label>
            <input type="text" id="address" placeholder="ul., numer, miasto" />
          </div>
          <div class="col">
            <label>Rodzaj instalacji / Badania</label>
            <select id="installationType">
              <option>Badanie okresowe</option>
              <option>Nowa</option>
              <option>Po Modernizacji</option>
              <option>Istniejąca</option>
            </select>
          </div>
        </div>
      </section>

      <!-- Warunki i przyrządy -->
      <section style="margin-top:14px">
        <h2 style="font-size:16px;margin-bottom:8px">Warunki i przyrządy</h2>
        <div class="row">
          <div class="col">
            <label>Układ sieci</label>
            <input type="text" id="networkType" value="TN" />
          </div>
          <div class="col">
            <label>Znamionowe napięcie względem ziemi (Uo)</label>
            <input type="text" id="uo" value="230 V" />
          </div>
          <div class="col">
            <label>Przyrząd pomiarowy</label>
            <input type="text" id="meter" value="MPI 507 SONEL" />
          </div>
        </div>
      </section>

      <!-- Obwody -->
      <section style="margin-top:14px">
        <h2 style="font-size:16px;margin-bottom:8px">Obwody</h2>
        <div class="card" style="padding:8px">
          <table id="circuitsTable">
            <thead>
              <tr>
                <th>Lp.</th>
                <th>Nazwa obwodu</th>
                <th>Ilość gniazd</th>
                <th>Zs [Ω]</th>
                <th>Ochrona skuteczna</th>
                <th>Usuń</th>
              </tr>
            </thead>
            <tbody></tbody>
          </table>
          <div style="display:flex;justify-content:flex-end;margin-top:8px">
            <button type="button" onclick="addCircuitRow()">Dodaj obwód</button>
          </div>
        </div>
      </section>

      <!-- RCD -->
      <section style="margin-top:14px">
        <h2 style="font-size:16px;margin-bottom:8px">Urządzenia różnicowoprądowe</h2>
        <div class="card" style="padding:8px">
          <table id="rcdTable">
            <thead>
              <tr>
                <th>Lp.</th><th>Obwód</th><th>Typ</th><th>In [mA]</th><th>T max [ms]</th><th>Ochrona skuteczna</th><th>Usuń</th>
              </tr>
            </thead>
            <tbody></tbody>
          </table>
          <div style="display:flex;justify-content:flex-end;margin-top:8px">
            <button type="button" onclick="addRcdRow()">Dodaj RCD</button>
          </div>
        </div>
      </section>

      <!-- Zabezpieczenia -->
      <section style="margin-top:14px">
        <h2 style="font-size:16px;margin-bottom:8px">Zabezpieczenia</h2>
        <div class="card" style="padding:8px">
          <table id="protectionsTable">
            <thead>
              <tr><th>Lp.</th><th>Nazwa</th><th>Typ</th><th>Ilość</th><th>Usuń</th></tr>
            </thead>
            <tbody></tbody>
          </table>
          <div style="display:flex;justify-content:flex-end;margin-top:8px">
            <button type="button" onclick="addProtectionRow()">Dodaj zabezpieczenie</button>
          </div>
        </div>
      </section>

      <!-- Uwagi -->
      <section style="margin-top:14px">
        <label>Uwagi</label>
        <textarea id="remarks" rows="4" placeholder="Uwagi do protokołu..."></textarea>

        <div style="margin-top:10px" class="row">
          <div class="col">
            <label>Ocena wizualna</label>
            <select id="visualEval"><option>Pozytywna</option><option>Negatywna</option></select>
          </div>
          <div class="col">
            <label>Orzeczenie</label>
            <select id="verdict"><option>Instalacja nadaje się do eksploatacji</option><option>Instalacja nie nadaje się do eksploatacji</option></select>
          </div>
        </div>

        <div style="margin-top:12px;display:flex;justify-content:space-between;align-items:center">
          <div class="muted">Dane zostaną zapisane w Google Sheets</div>
          <div>
            <button type="submit">Zapisz</button>
            <button type="button" class="ghost" onclick="downloadJSON()">Pobierz JSON</button>
          </div>
        </div>
      </section>
    </form>

    <div id="msg" style="margin-top:8px"></div>
  </div>

  <script>
    // ====== LISTY DO UZUPEŁNIENIA ======
    // 🔧 Dodaj własne typy RCD lub zabezpieczeń poniżej:
    const RCD_TYPES = ['40A/3F', '25A/3F', '25A/1F', '25A/1F', 'B16/1F', 'B10/1F']; // typy RCD
    const PROTECTION_TYPES = ['B16/1F', 'B10/1F', 'B16/3F', 'D', 'E', 'G']; // typy zabezpieczeń
    // ====================================

    function refreshTableIndices(tableEl){
      const tbody = tableEl.querySelector('tbody');
      Array.from(tbody.children).forEach((tr, idx) => tr.children[0].textContent = idx + 1);
    }

    function removeRowAndRefresh(button){
      const tr = button.closest('tr');
      const table = button.closest('table');
      tr.remove();
      refreshTableIndices(table);
    }

    function createSelect(options, selected=''){
      const s = document.createElement('select');
      options.forEach(opt=>{
        const o = document.createElement('option');
        o.textContent = opt;
        if(opt===selected) o.selected = true;
        s.appendChild(o);
      });
      return s;
    }

    function addCircuitRow(preset = {}) {
      const tbody = document.querySelector('#circuitsTable tbody');
      const tr = document.createElement('tr');
      tr.innerHTML = `
        <td></td>
        <td><input type="text" value="${preset.name || ''}" placeholder="np.Kuchnia"></td>
        <td><input type="number" min="0" value="${preset.sockets || ''}"></td>
        <td><input type="text" value="${preset.zs || ''}"></td>
        <td><select><option>Tak</option><option>Nie</option></select></td>
        <td><button type="button" onclick="removeRowAndRefresh(this)" style="background:#fee;color:#a00;border:none;border-radius:6px;padding:4px 8px">🗑</button></td>`;
      tbody.appendChild(tr);
      refreshTableIndices(document.querySelector('#circuitsTable'));
    }

    function addRcdRow(preset = {}) {
      const tbody = document.querySelector('#rcdTable tbody');
      const tr = document.createElement('tr');
      const tdType = document.createElement('td');
      tdType.appendChild(createSelect(RCD_TYPES, preset.type || ''));
      tr.innerHTML = `
        <td></td>
        <td><input type="text" value="${preset.circuit || ''}"></td>
        <td></td>
        <td><input type="number" value="${preset.in || ''}"></td>
        <td><input type="number" value="${preset.tmax || ''}"></td>
        <td><select><option>Tak</option><option>Nie</option></select></td>
        <td><button type="button" onclick="removeRowAndRefresh(this)" style="background:#fee;color:#a00;border:none;border-radius:6px;padding:4px 8px">🗑</button></td>`;
      tr.children[2].replaceWith(tdType);
      tbody.appendChild(tr);
      refreshTableIndices(document.querySelector('#rcdTable'));
    }

    function addProtectionRow(preset = {}) {
      const tbody = document.querySelector('#protectionsTable tbody');
      const tr = document.createElement('tr');
      const tdType = document.createElement('td');
      tdType.appendChild(createSelect(PROTECTION_TYPES, preset.type || ''));
      tr.innerHTML = `
        <td></td>
        <td><input type="text" value="${preset.name || 'TM'}"></td>
        <td></td>
        <td><input type="number" min="0" value="${preset.count || 1}"></td>
        <td><button type="button" onclick="removeRowAndRefresh(this)" style="background:#fee;color:#a00;border:none;border-radius:6px;padding:4px 8px">🗑</button></td>`;
      tr.children[2].replaceWith(tdType);
      tbody.appendChild(tr);
      refreshTableIndices(document.querySelector('#protectionsTable'));
    }

    function downloadJSON(){
      const data = { circuits: [], rcds: [], protections: [] };
      document.querySelectorAll('#circuitsTable tbody tr').forEach(tr=>{
        const i = tr.querySelectorAll('input,select');
        data.circuits.push({name:i[0].value, sockets:i[1].value, zs:i[2].value, ok:i[3].value});
      });
      document.querySelectorAll('#rcdTable tbody tr').forEach(tr=>{
        const i = tr.querySelectorAll('input,select');
        data.rcds.push({circuit:i[0].value, type:i[1].value, in:i[2].value, tmax:i[3].value, ok:i[4].value});
      });
      document.querySelectorAll('#protectionsTable tbody tr').forEach(tr=>{
        const i = tr.querySelectorAll('input,select');
        data.protections.push({name:i[0].value, type:i[1].value, count:i[2].value});
      });
      const blob = new Blob([JSON.stringify(data,null,2)],{type:'application/json'});
      const a = document.createElement('a'); a.href=URL.createObjectURL(blob); a.download='protokol.json'; a.click();
    }

async function handleSubmit(e) {
  e.preventDefault();

  const data = {
    protocolNumber: document.getElementById('protocolNumber').value,
    client: document.getElementById('client').value,
    address: document.getElementById('address').value,
    installationType: document.getElementById('installationType').value,
    networkType: document.getElementById('networkType').value,
    uo: document.getElementById('uo').value,
    meter: document.getElementById('meter').value,
    remarks: document.getElementById('remarks').value,
    visualEval: document.getElementById('visualEval').value,
    verdict: document.getElementById('verdict').value,
    circuits: [],
    rcds: [],
    protections: []
  };

  document.querySelectorAll('#circuitsTable tbody tr').forEach(tr=>{
    const i = tr.querySelectorAll('input,select');
    data.circuits.push({name:i[0].value, sockets:i[1].value, zs:i[2].value, ok:i[3].value});
  });
  document.querySelectorAll('#rcdTable tbody tr').forEach(tr=>{
    const i = tr.querySelectorAll('input,select');
    data.rcds.push({circuit:i[0].value, type:i[1].value, in:i[2].value, tmax:i[3].value, ok:i[4].value});
  });
  document.querySelectorAll('#protectionsTable tbody tr').forEach(tr=>{
    const i = tr.querySelectorAll('input,select');
    data.protections.push({name:i[0].value, type:i[1].value, count:i[2].value});
  });

  // 🔗 Wstaw swój własny URL z Apps Script tutaj:
  const scriptURL = 'https://script.google.com/macros/s/AKfycbwagJPu5VjxSe0pll79FwK_xYpcR1I3q6wfzAmjkEpxud5wk1RX3JXupo6Xp3oshWls/exec';

  const msg = document.getElementById('msg');
  msg.textContent = "Wysyłanie danych...";

  try {
    const res = await fetch(scriptURL, {
      method: 'POST',
      body: JSON.stringify(data),
      headers: { 'Content-Type': 'application/json' }
    });
    const result = await res.json();
    msg.textContent = "✅ " + result.message;
  } catch (err) {
    msg.textContent = "❌ Błąd zapisu: " + err.message;
  }
}
    // startowe dane
    addCircuitRow({ name: 'Kuchnia', sockets: 5 });
    addCircuitRow({ name: 'Łazienka', sockets: 2 });
    addCircuitRow({ name: 'Pokój 1', sockets: 3 });
    addRcdRow({ circuit:'Gniazdkowy', type:'', in:'', tmax:'' });
    addRcdRow({ circuit:'Oświetleniowy', type:'', in:'', tmax:''});
  </script>
</body>
</html>
