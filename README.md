# 🖥️ Active Directory Homelab
  <p>I have built an active directory lab with VMWare with the following components:</p>
        <p> - Windows Server 2022 - acting as the Domain Controller</p>
        <p> - Windows 10 Enterprise machines acting as clients in the network</p>
        <p> - Kali Linux machine used as the attack box to compromise the Domain Controller in an internal pentest</p>
  <b> The pentest was conducted using the following methods:</b>
        <p> - Scanning and enumeration using NMAP and Bloodhound</p>
        <p> - LLMNR and IPv6 spoofing using tools such as responder to catch NTLM hashes</p>
        <p> - SAM dumps using tools such as Responder and ntlmrelayx</p>
        <p> - Pass-the-hash attacks and passaword spraying using crackmapexec and Impacket tools to relay </p>
        <p> - SMB relay attacks to gain interactive shells on the target machines </p>
        <p> - Kerberoasting</p>
        <p> - LSAdumps on target machines with Mimikatz</p>
        <p> - NTSD.dit dumps form the Domain Controller to retrieve domain credential hashes using Secretsdump</p>
        <p> - Password cracking with Hashcat</p>
