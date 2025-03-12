This is a comprehensive ncurses-based TUI for managing fail2ban on Linux. Here's what the tool provides:

### Features:

1. **Dashboard View**
   - Lists all active jails with their current status
   - Shows currently failed/banned IPs and total counts
   - Detailed view of selected jail with monitored files and banned IPs

2. **Log Viewer**
   - Real-time display of fail2ban logs
   - Color-coded entries (red for errors, yellow for warnings, green for bans)
   - Filtering capability to search for specific entries
   - Scrollable interface for viewing history

3. **Management Functions**
   - Ability to unban specific IPs
   - Restart individual jails
   - Monitor jail statistics in real-time

### Usage:
1. Save the script to a file (e.g., `fail2ban_tui.py`)
2. Make it executable: `chmod +x fail2ban_tui.py`
3. Run with sudo: `sudo ./fail2ban_tui.py`

### Navigation:
- Use arrow keys to navigate
- Key shortcuts for all functions are shown at the bottom
- [D]ashboard and [L]ogs to switch between views
- [Q]uit to exit

The tool requires sudo privileges since fail2ban management requires root access. It will automatically update every few seconds to show the latest data.
