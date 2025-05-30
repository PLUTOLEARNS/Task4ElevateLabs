# Windows Firewall Configuration and Testing Task (Task 4)
## Task 4

### What's Covered
- **Firewall Access**: Multiple methods to open Windows Firewall with Advanced Security
- **Rule Management**: Viewing, creating, and deleting firewall rules
- **Practical Testing**: Real-world testing of firewall rules using various methods
- **Command-Line Operations**: PowerShell commands for firewall management

### Objectives
1. Navigate Windows Firewall with Advanced Security interface
2. Create blocking rules for specific ports (Telnet - Port 23)
3. Create allowing rules for services (SSH - Port 22)
4. Test firewall effectiveness using multiple verification methods
5. Clean up test configurations properly

## Contents

### 1. Firewall Access Methods
- GUI access via `wf.msc` run command
- Alternative access through Control Panel and Settings
- PowerShell command-line interface

### 2. Rule Management
- **Viewing Rules**: Both inbound and outbound rule inspection
- **Creating Rules**: Step-by-step rule creation process
- **Testing Rules**: Verification methods using telnet and PowerShell
- **Removing Rules**: Proper cleanup procedures

### 3. Practical Examples
- **Block Rule**: Telnet (Port 23) blocking configuration
- **Allow Rule**: SSH (Port 22) allowing configuration
- **Testing Methods**: Connection attempts and PowerShell testing

### Traffic Filtering Process
- Packet inspection against predefined rules
- Rule precedence and order processing
- First matching rule determines action

### Rule Types
- **Inbound Rules**: Control incoming traffic
- **Outbound Rules**: Control outgoing traffic

### Network Profiles
- **Domain**: Corporate network environments
- **Private**: Home/trusted networks
- **Public**: Untrusted public networks

## Default Behavior
- **Inbound Traffic**: Blocked by default (whitelist approach)
- **Outbound Traffic**: Allowed by default (can create block rules)
