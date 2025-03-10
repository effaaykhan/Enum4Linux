# Enum4Linux
- enum4linux is a tool for enumerating information from Windows and Samba systems. It is a command-line tool that can be used to gather information about the target system, such as usernames, password policies, shares, and more.

### Installation
To install enum4linux in Kali Linux, you can use the following command:

```
sudo apt install enum4linux
```
### Usage
Once installed, you can use enum4linux to enumerate information from a target system. Here's an example of how to use enum4linux:

```
enum4linux -a <target>
```

This command performs a full basic enumeration on the target system. It gathers information such as:
- User accounts
- Share information
- Group and member information
- Password policy information
- OS information
- Network information
- Running process information

Replace `<target>` with the target system or network.

enum4linux can be used to gather valuable information about the target system, which can be used for further analysis and attack planning. It is a valuable tool for security professionals and penetration testers to gain an understanding of the target system's security posture.
