# Privilege Escalation Mindmap

## Overview
This repository provides a comprehensive **mindmap** for **privilege escalation techniques** in Windows and Linux environments, designed for red teamers, penetration testers, and security researchers. It serves as a quick-reference guide for scenarios where automated tools like **LinPEAS** or **WinPEAS** cannot be used (e.g., due to stealth requirements, restricted environments, or endpoint detection).

The mindmap visually organizes privilege escalation methods, including misconfigurations, weak permissions, and exploitation techniques, to help you identify and exploit vulnerabilities at a glance. This project is actively developed and will be continuously updated with new techniques and improvements.

## Features
- **Visual Mindmap**: A clear, structured overview of privilege escalation techniques for both Windows and Linux.
- **Tool-Free Methods**: Focuses on manual enumeration and exploitation, ideal for environments where tools are restricted.
- **Regular Updates**: Continuously evolving to include the latest techniques and best practices.
- **Red Team Focus**: Covers methods like unquoted service paths, weak registry permissions, SUID binaries, cron job abuse, and more, tailored for offensive security.

## Getting Started
1. **View the Mindmap**:
   - Open the mindmap file (`privilege_escalation_mindmap.[format]`) in a compatible viewer (e.g., XMind, FreeMind, or a web-based tool).
   - The mindmap is organized by platform (Windows/Linux) and technique (e.g., misconfigurations, kernel exploits).
2. **Explore Techniques**:
   - Each node provides a brief description, enumeration steps, and exploitation methods.
   - Cross-references to related techniques for comprehensive understanding.
3. **Use Cases**:
   - Ideal for red team engagements, CTF challenges, or learning privilege escalation in restricted environments.

## Example Techniques Covered
- **Windows**:
  - Unquoted service paths
  - Weak service/registry permissions
  - DLL hijacking
  - Scheduled task abuse
- **Linux**:
  - Sudo misconfigurations
  - Cron job abuse
  - SUID/SGID binaries
  - Weak file permissions

## Why This Repo?
In some scenarios, automated tools like LinPEAS or WinPEAS may trigger endpoint detection, be blocked by network restrictions, or require excessive setup. This mindmap provides a lightweight, manual approach to privilege escalation, enabling stealthy and effective enumeration without relying on external tools.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Add or update techniques in the mindmap.
3. Submit a pull request with a clear description of changes.

Please report issues or suggest improvements via the [Issues](https://github.com/yourusername/yourrepo/issues) tab.

## Roadmap
- Add hybrid AD-Linux environment techniques (e.g., Kerberoasting on Linux servers).
- Include example scripts for manual enumeration.
- Support additional mindmap formats for broader compatibility.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
Inspired by tools like LinPEAS, WinPEAS, and resources like [GTFOBins](https://gtfobins.github.io/) and [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings).

---
*Last Updated: June 2025*
