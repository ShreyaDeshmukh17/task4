# task4

# Task 4: Configure and Use Firewall on Windows

## Objective
Set up and test basic firewall rules to allow or block specific network traffic using Windows Defender Firewall.

## Tools Used
- Windows Defender Firewall (Advanced Settings)
- Command Prompt
- Telnet Client (for testing)

## Steps Performed

1. **Open Firewall Settings**  
   Opened Windows Defender Firewall with `wf.msc`.

2. **View Existing Rules**  
   Checked current inbound rules to understand default configuration.

3. **Block Port 23 (Telnet)**  
   Created a new inbound rule to block TCP traffic on port 23.

4. **Test Block Rule**  
   Enabled Telnet client and ran:  
Result: Connection failed (blocked by firewall).

5. **Allow Port 22 (SSH)**  
Created a new inbound rule to allow TCP traffic on port 22.

6. **Remove Test Rule**  
Deleted the Telnet block rule to restore the original state.

## Summary
Windows Firewall filters network traffic based on rules. It allows or blocks data packets depending on port, protocol, IP address, and direction. This helps protect the system from unauthorized access and threats.

