# UPSHELL AUTOMATIC

**Coded by:** Latip176

## Description

UPSHELL AUTOMATIC is a tool designed to automate the process of uploading a shell to WordPress sites by leveraging the plugin and theme upload features within the WordPress admin panel. It authenticates with the provided credentials, attempts to upload the shell, and logs the results for easy reference.

## Features

- **Automated Shell Upload**: Uploads shells via WordPress plugin or theme installation pages.
- **Login Authentication**: Authenticates with the target WordPress site using provided credentials.
- **Error Handling**: Detects and reports common issues such as Cloudflare protection, incorrect login credentials, and more.
- **Result Logging**: Saves successful shell uploads to a results file for further analysis.

## Requirements

- **Python 3.x**
- **Requests Library**
- **BeautifulSoup Library**

If the required libraries are not installed, the script will automatically attempt to install them.

## Usage

1. **Prepare your input file**: Create a text file containing the list of WordPress sites with credentials in the format `wp-login.php#username@password`.
2. **Run the Script**: Execute the script and provide the path to your input file when prompted.
3. **Review Results**: The script will save the URLs of successfully uploaded shells in the `results/shells.txt` file.

```bash
python3 upshell.py
```
