Multi-Pointer for KDE Plasma
An advanced system utility that enables the use of multiple, independent, and simultaneous mouse cursors on the KDE Plasma desktop.

Multi-Pointer breaks the "one cursor per machine" barrier. Unlock new workflows for collaboration, boost your productivity, and improve your system's accessibility with a tool that is seamlessly integrated into your desktop.

✨ Why Multi-Pointer?
Imagine the possibilities when two or more users can interact with the same screen, at the same time, each with their own cursor.

Local Collaboration: Perfect for pair programming, pair designing, or any collaborative task. One user can write code while the other navigates documentation.

Enhanced Accessibility: Users with specific motor needs can combine different input devices (like a traditional mouse and a trackball), operating them independently for greater comfort and control.

Presentations and Education: While a presenter uses one cursor to highlight key points, an assistant can use another to manage slides, answer questions in the chat, or open files.

Productivity for Ambidextrous Users: Use a mouse in each hand to perform parallel tasks, like editing a document with one hand while browsing the web with the other, optimizing your workflow.

🚀 Features
Multiple Independent Cursors: Real, transparent support for several cursors on the screen.

Native KDE Integration: Configure everything directly in KDE Plasma's System Settings. No need for command-line tools for daily use.

Robust System Service: Runs as a systemd daemon, ensuring stability and availability from boot.

Security First: Uses Polkit for secure permission management, ensuring only authorized users can change system settings.

Easy to Install: Distributed as a .deb package for a simple and clean installation on Debian-based systems (Kubuntu, etc.).

⚙️ Getting Started (Installation)
The easiest way to install Multi-Pointer is via the .deb package provided on our Releases page.

Download the Package: Go to the Releases section and download the latest .deb file.

Install via Terminal: Open a terminal in the folder where you downloaded the file and run:

sudo apt install ./multi-pointer_*.deb

apt will handle all necessary dependencies automatically.

Log Out and Back In: To ensure all components are loaded correctly, it is recommended to log out and start a new session.

🖱️ How to Use
After installation, configuration is very simple:

Open KDE Plasma's System Settings.

Navigate to Hardware > Input Devices.

In the side menu, you will find a new section called Multi-Pointer.

In this panel, you can:

Enable or disable the service globally.

See a list of all mice (or pointer devices) connected to your computer.

Assign each physical device to a "Virtual Pointer" (Pointer 1, Pointer 2, etc.).

That's it! Changes are applied instantly.

🛠️ Building from Source
If you prefer to compile the project yourself, follow the detailed instructions in our Technical Manual.

🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Please follow our Contribution Guide to learn how to submit your improvements.

📜 License
This project is licensed under the GNU General Public License v3.0. See the LICENSE file for more details.
