<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

        :root {
            --navy-blue: #004C91; /* Official NFCU-style Blue */
            --navy-gold: #FFC72C; /* Accent Gold */
            --navy-light: #f1f5f9;
            --text-dark: #1a202c;
            --white: #ffffff;
            --success: #2f855a;
        }

        body { font-family: 'Roboto', sans-serif; margin: 0; padding: 10px; color: var(--text-dark); background: transparent; }

        .cockpit-container {
            background: var(--white);
            border-radius: 2px; /* Crisp, formal edges */
            box-shadow: 0 4px 20px rgba(0,0,0,0.15);
            border: 1px solid #cbd5e0;
            max-width: 480px;
            overflow: hidden;
        }

        /* Military-Branded Header */
        .brand-header {
            background: var(--navy-blue);
            color: white;
            padding: 14px 20px;
            font-weight: 700;
            font-size: 13px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 3px solid var(--navy-gold);
        }

        .search-area { padding: 18px 20px 10px 20px; background: white; }
        #widgetSearch {
            width: 100%;
            padding: 12px;
            border: 1px solid #a0aec0;
            font-size: 14px;
            box-sizing: border-box;
            background-color: #fcfcfc;
        }
        #widgetSearch:focus { border-color: var(--navy-blue); outline: none; background: #fff; }

        .nav-pills { display: flex; background: var(--navy-light); border-bottom: 1px solid #cbd5e0; }
        .pill {
            flex: 1; padding: 12px 5px; border: none;
            background: transparent; color: var(--navy-blue); font-size: 11px;
            font-weight: 700; cursor: pointer; text-transform: uppercase;
        }
        .pill.active { background: var(--white); color: var(--navy-blue); border-top: 2px solid var(--navy-blue); }

        .content-pane { padding: 20px; min-height: 320px; display: none; }
        .content-pane.active { display: block; }

        .live-status { font-size: 10px; font-weight: 700; color: #718096; margin-bottom: 12px; display: flex; align-items: center; letter-spacing: 0.5px; }
        .pulse { width: 7px; height: 7px; background: var(--success); border-radius: 50%; margin-right: 8px; animation: pulse-anim 2s infinite; }
        @keyframes pulse-anim { 0% { box-shadow: 0 0 0 0 rgba(47, 133, 90, 0.7); } 70% { box-shadow: 0 0 0 8px rgba(47, 133, 90, 0); } 100% { box-shadow: 0 0 0 0 rgba(47, 133, 90, 0); } }

        /* Rates Table Style */
        .data-row {
            background: var(--white); padding: 10px 0;
            display: flex; justify-content: space-between; align-items: center;
            border-bottom: 1px solid #edf2f7;
        }
        .data-label { font-size: 13px; font-weight: 500; }
        .data-value { font-weight: 700; color: var(--navy-blue); font-size: 14px; }

        .copy-btn { font-size: 9px; background: var(--navy-blue); color: white; border: none; padding: 4px 8px; border-radius: 2px; cursor: pointer; margin-left: 10px; font-weight: bold; text-transform: uppercase; }

        /* Service Script Style */
        .script-select { width: 100%; padding: 10px; border: 1px solid #a0aec0; margin-bottom: 12px; font-weight: 700; color: var(--navy-blue); }
        .script-bubble { background: #f0f7ff; border-left: 4px solid var(--navy-blue); padding: 15px; font-size: 14px; line-height: 1.6; color: #2d3748; }

        /* Member FAQ Style */
        .faq-group { margin-bottom: 16px; }
        .faq-q { font-weight: 700; font-size: 12px; color: var(--navy-blue); text-transform: uppercase; display: block; margin-bottom: 2px; }
        .faq-a { font-size: 13px; color: #4a5568; line-height: 1.4; }

        .no-results { display: none; padding: 50px 20px; text-align: center; color: #718096; font-size: 14px; }
    </style>
</head>
<body>

<div class="cockpit-container">
    <div class="brand-header">
        <span>MEMBER-FIRST ASSIST</span>
        <span style="font-size: 10px; color: var(--navy-gold);">SERVICE • INTEGRITY</span>
    </div>

    <div class="search-area">
        <input type="text" id="widgetSearch" placeholder="Search VA Loans, Certificates, or 'Routing'..." onkeyup="universalSearch()">
    </div>

    <div class="nav-pills">
        <button id="pill-rates" class="pill active" onclick="manualTab('rates')">Loan & Div Rates</button>
        <button id="pill-scripts" class="pill" onclick="manualTab('scripts')">Service Scripts</button>
        <button id="pill-faq" class="pill" onclick="manualTab('faq')">Member FAQ</button>
    </div>

    <div id="rates" class="content-pane active">
        <div class="live-status"><span class="pulse"></span>FED RATE SYNC: ACTIVE</div>
        <div class="searchable-item data-row">
            <span class="data-label">VA Home Loan (30Y Fixed)</span>
            <span><span class="data-value">6.25%</span> <button class="copy-btn" onclick="copyValue('6.25%')">Copy</button></span>
        </div>
        <div class="searchable-item data-row">
            <span class="data-label">New Auto (Active Duty)</span>
            <span><span class="data-value">4.99%</span> <button class="copy-btn" onclick="copyValue('4.99%')">Copy</button></span>
        </div>
        <div class="searchable-item data-row">
            <span class="data-label">12-Month Share Certificate</span>
            <span><span class="data-value">5.30% APY</span> <button class="copy-btn" onclick="copyValue('5.30%')">Copy</button></span>
        </div>
        <div class="searchable-item data-row">
            <span class="data-label">Flagship Checking APY</span>
            <span><span class="data-value">0.45% APY</span> <button class="copy-btn" onclick="copyValue('0.45%')">Copy</button></span>
        </div>
    </div>

    <div id="scripts" class="content-pane">
        <select id="situationSelect" class="script-select" onchange="updateScriptText()">
            <option value="welcome">Member Greeting</option>
            <option value="military">PCS / Moving Transition</option>
            <option value="fraud">Fraudulent Activity</option>
        </select>
        <div id="scriptBox" class="searchable-item script-bubble">
            "Thank you for your service and for calling our support team. This is [Name], how can I assist you today?"
        </div>
        <button class="copy-btn" style="width:100%; margin-top:15px; padding:12px; font-size:11px" onclick="copyValue(document.getElementById('scriptBox').innerText)">Copy Script to Member Profile</button>
    </div>

    <div id="faq" class="content-pane">
        <div class="searchable-item faq-group">
            <span class="faq-q">Routing Transit Number</span>
            <span class="faq-a">256074112 <button class="copy-btn" onclick="copyValue('256074112')">Copy</button></span>
        </div>
        <div class="searchable-item faq-group">
            <span class="faq-q">Zelle Limit (Standard)</span>
            <span class="faq-a">$1,000 daily / $3,000 monthly.</span>
        </div>
        <div class="searchable-item faq-group">
            <span class="faq-q">International Wire Fee</span>
            <span class="faq-a">$25.00 flat fee for members. <button class="copy-btn" onclick="copyValue('$25.00')">Copy</button></span>
        </div>
        <div class="searchable-item faq-group">
            <span class="faq-q">ATM Fee Rebates</span>
            <span class="faq-a">Up to $20/month for Flagship Checking.</span>
        </div>
    </div>

    <div id="noResults" class="no-results">Member record or keyword not found.</div>
</div>

<script>
    function switchTab(id) {
        const panes = document.getElementsByClassName("content-pane");
        const pills = document.getElementsByClassName("pill");
        for (let i = 0; i < panes.length; i++) {
            panes[i].style.display = "none";
            panes[i].classList.remove("active");
            pills[i].classList.remove("active");
        }
        document.getElementById(id).style.display = "block";
        document.getElementById(id).classList.add("active");
        document.getElementById('pill-' + id).classList.add('active');
    }

    function manualTab(id) {
        document.getElementById('widgetSearch').value = "";
        universalSearch();
        switchTab(id);
    }

    function updateScriptText() {
        const scripts = {
            welcome: '"Thank you for your service and for calling our support team. This is [Name], how can I assist you today?"',
            military: '"I understand you are preparing for a PCS. I can help set up your travel notifications and discuss military move loans."',
            fraud: '"I am immediately securing your accounts. Let\'s verify your most recent authorized transaction together."'
        };
        document.getElementById('scriptBox').innerText = scripts[document.getElementById('situationSelect').value];
    }

    function universalSearch() {
        const query = document.getElementById('widgetSearch').value.toLowerCase();
        const items = document.querySelectorAll('.searchable-item');
        let matchesByTab = new Set();
        let totalFound = 0;

        items.forEach(item => {
            const isMatch = item.innerText.toLowerCase().includes(query);
            item.style.display = isMatch ? "block" : "none";
            if (isMatch) {
                matchesByTab.add(item.closest('.content-pane').id);
                totalFound++;
            }
        });

        if (query.length > 0) {
            const activeTabId = document.querySelector('.content-pane.active').id;
            if (!matchesByTab.has(activeTabId) && matchesByTab.size > 0) {
                switchTab(Array.from(matchesByTab)[0]);
            }
        }

        document.getElementById('noResults').style.display = (totalFound === 0 && query.length > 0) ? 'block' : 'none';
    }

    function copyValue(val) {
        navigator.clipboard.writeText(val);
        const btn = event.target;
        const oldText = btn.innerText;
        btn.innerText = "COPIED";
        btn.style.background = "#FFC72C";
        btn.style.color = "#004C91";
        setTimeout(() => {
            btn.innerText = oldText;
            btn.style.background = "";
            btn.style.color = "";
        }, 1200);
    }
</script>

</body>
</html>
