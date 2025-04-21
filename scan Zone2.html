<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nmap Scan Zone</title>
    <style>
        table {
            border-collapse: collapse;
            width: 100%;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #f4f4f4;
        }
        textarea {
            resize: none;
            width: 80%;
            height: 50px;
        }
    </style>
    <script>
        // Array of commands with descriptions
        const commands = [
            { type: "-sS", description: "TCP SYN port scan (Default)" },
            { type: "-sT", description: "TCP connect port scan (Default without root privilege)" },
            { type: "-sU", description: "UDP port scan" },
            { type: "-sA", description: "TCP ACK port scan" },
            { type: "-sW", description: "TCP Window port scan" },
            { type: "-sM", description: "TCP Maimon port scan" },
            { type: "-sL", description: "No Scan. List targets only" },
            { type: "-sn", description: "Disable port scanning. Host discovery only" },
            { type: "-Pn", description: "Disable host discovery. Port scan only" },
            { type: "-PS", description: "TCP SYN discovery on port x. Port 80 by default" },
            { type: "-PA", description: "TCP ACK discovery on port x. Port 80 by default" },
            { type: "-PU", description: "UDP discovery on port x. Port 40125 by default" },
            { type: "-PR", description: "ARP discovery on local network" },
            { type: "-n", description: "Never do DNS resolution" },
            { type: "-p-", description: "Port scan all ports" },
            { type: "-p http,https", description: "Port scan from service name" },
            { type: "-F", description: "Fast port scan (100 ports)" },
            { type: "-top-ports 2000", description: "Port scan the top x ports" },
            { type: "-p-65535", description: "Leaving off initial port in range makes the scan start at port 1" },
            { type: "-p0-", description: "Leaving off end port in range makes the scan go through to port 65535" },
            { type: "-sV", description: "Attempts to determine the version of the service running on port" },
            { type: "-sV -version-intensity 8", description: "Intensity level 0 to 9. Higher number increases correctness" },
            { type: "-sV -version-light", description: "Enable light mode. Lower correctness but faster" },
            { type: "-sV -version-all", description: "Enable intensity level 9. Higher correctness but slower" },
            { type: "-A", description: "Enables OS detection, version detection, script scanning, and traceroute" },
            { type: "-O", description: "Remote OS detection using TCP/IP stack fingerprinting" },
            { type: "-T0", description: "Paranoid (0) Intrusion Detection System evasion" },
            { type: "-T5", description: "Insane (5) speeds scan; assumes fast network" },
            { type: "-sC", description: "Scan with default NSE scripts" },
            { type: "-script=banner", description: "Scan with a single script. Example banner" },
            { type: "-script=http*", description: "Scan with a wildcard. Example http" },
            { type: "-script=http,banner", description: "Scan with two scripts. Example http and banner" },
            { type: "-f", description: "Requested scan uses tiny fragmented IP packets" },
            { type: "-D", description: "Send scans from spoofed IPs" },
            { type: "-g 53", description: "Use given source port number" },
            { type: "-proxies", description: "Relay connections through HTTP/SOCKS4 proxies" },
            { type: "-data-length 200", description: "Appends random data to sent" }
        ];

        // Function to dynamically populate the table
        function populateTable() {
            const ip = document.getElementById('ipInput').value || "192.168.1.1"; // Default IP if none entered
            const tableBody = document.getElementById('commandTableBody');
            tableBody.innerHTML = ""; // Clear existing rows

            commands.forEach(command => {
                const row = document.createElement('tr');

                // Command & Description column
                const commandCell = document.createElement('td');
                commandCell.innerHTML = `nmap ${ip} ${command.type} <br><span style="font-size: 0.9em; color: gray;">(${command.description})</span>`;
                row.appendChild(commandCell);

                // Scan Run column
                const scanRunCell = document.createElement('td');
                scanRunCell.innerHTML = `
                    <label><input type="checkbox" name="scanRun" value="Yes"> Yes</label>
                    <label><input type="checkbox" name="scanRun" value="No"> No</label>
                `;
                row.appendChild(scanRunCell);

                // Issues Found column
                const issuesFoundCell = document.createElement('td');
                issuesFoundCell.innerHTML = `
                    <label><input type="checkbox" name="issuesFound" value="Yes"> Yes</label>
                    <label><input type="checkbox" name="issuesFound" value="No"> No</label>
                `;
                row.appendChild(issuesFoundCell);

                // Comments column
                const commentsCell = document.createElement('td');
                commentsCell.innerHTML = `<textarea name="comments" placeholder="Enter open ports..."></textarea>`;
                row.appendChild(commentsCell);

                // Append the row to the table body
                tableBody.appendChild(row);
            });
        }

        // Update table dynamically when IP is changed
        function updateIP() {
            populateTable();
        }

        // Populate table on initial load
        window.onload = populateTable;
    </script>
</head>
<body>
    <h1>Nmap Scan Zone</h1>
    <label for="ipInput">Enter Target IP Address:</label>
    <input type="text" id="ipInput" placeholder="Enter IP here" oninput="updateIP()">
    
    <table>
        <thead>
            <tr>
                <th>Scan Command & Description</th>
                <th>Scan Run</th>
                <th>Issues Found</th>
                <th>Comments (Open Ports Found)</th>
            </tr>
        </thead>
        <tbody id="commandTableBody">
            <!-- Rows will be dynamically populated here -->
        </tbody>
    </table>
</body>
</html>
