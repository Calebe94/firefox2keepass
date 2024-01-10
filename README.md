# firefox2keepass 🦊🔐

This Shell script is designed to convert logins exported from Firefox into a CSV file compatible with KeePass. It processes the exported CSV containing login data and arranges it into a format recognized by KeePass.

## Notes 📝

- 🚨 The script assumes the CSV file follows the expected structure exported by Firefox.
- 🚨 Ensure the exported CSV file is compatible with the script's expected format to avoid errors.
- 🚨 The output CSV (`keepass_ready.csv`) is formatted to suit KeePass; import it into KeePass for password management.

## Usage 🚀

To utilize this script, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/firefox-logins-to-keepass-csv.git
   cd firefox-logins-to-keepass-csv
   ```

2. **Run the script:**

   ```bash
   ./firefox2keepass.sh exported_firefox_logins.csv > keepass_ready.csv
   ```

Replace `exported_firefox_logins.csv` with the filename of your exported Firefox logins CSV file. The script will generate a `keepass_ready.csv` file in a format suitable for KeePass.

# Developer

| <img src="https://github.com/Calebe94.png?size=200" alt="Edimar Calebe Castanho"> |
|:---------------------------------------------------------------------------------:|
| [Edimar Calebe Castanho (Calebe94)](https://github.com/Calebe94)                  |

# License

All software is covered under [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).
