*This project has been created as part of the 42 curriculum by aanouer.*

# 🌐 NetPractice

## Description

NetPractice is a hands-on project to learn the basics of **computer networking**.
The goal is to fix broken network diagrams by correctly configuring **IP addresses**, **subnet masks**, and **default gateways**, so that all devices (hosts and routers) can properly communicate with each other.

The project includes 10 levels of increasing difficulty, each simulating a small network that needs to be repaired.

## Instructions

1. Download and extract the project files into a folder.
2. Run the training interface with:
   ```bash
   ./run.sh
   ```
3. If it doesn't open automatically, run it manually:
   ```bash
   python3 -m http.server 49242
   ```
   Then open `http://localhost:49242` in your browser.
4. Enter `your login` in the field to load your personal configuration.
5. Solve each level by editing the unshaded fields until the status shows **OK**.
6. Click **Get my config** to export your configuration file for that level.
7. Repeat for all 10 levels.

### Submission

All 10 exported configuration files (one per level) must be placed at the **root of the repository**.

## Resources

- [IT Dose - Networking YouTube Playlist](https://www.youtube.com/watch?v=q6tUCEUqxTQ&list=PL8s4OGp0649_e_Wbz5MlBgW5rBW-9hD0c)
- Networking concepts studied: **TCP/IP addressing**, **subnet masks**, **default gateways**, **routers and switches**, **OSI layers**

**AI usage:** I used AI to help me understand networking concepts and to clarify things I found confusing along the way.
