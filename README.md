# DirReaper                          
                                      
```                                  
   ...reap what you sow...           
          /                          
  _______/                           
 /  ____/                            
/  /                                 
__/ 
```                                       

## Author

*   **Name:** Clive Akporube
*   **GitHub:** [whoami-pantheon](https://github.com/whoami-pantheon)
*   **LinkedIn:** [Clive (Kaiser) Akporube](https://linkedin.com/in/clive-kaiser)

**Fear the Reaper. Harvest the directories.** 

DirReaper is a tool created to traverse the forgotten paths, a scythe to harvest the fruits of directory traversal vulnerabilities. It crawls, it seeks, it reaps.

## Features

*   **Fast and Asynchronous:** Built with `asyncio` and `aiohttp` for high-speed, concurrent crawling.
*   **Crawls with a purpose:** Hunts for files and folder on a given URL (Target should suffer from Directory Traversal vulnerability for maximum impact) .
*   **Multi-URL harvesting:** Can reap from a list of URLs in a file.
*   **Saves the harvest:** Stores the found directory paths in a file for your... analysis.
*   **Silent and deadly:** No unnecessary noise, just the sweet sound of found paths.

## Installation

To wield the Reaper, you must first prepare its environment.

1.  Create a virtual environment:
    ```bash
    python3 -m venv venv
    ```
2.  Activate it:
    ```bash
    source venv/bin/activate
    ```
3.  Summon its dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Unleash the Reaper with a simple command.

**To reap a single URL:**

```bash
python3 dir_reaper.py <url>
```

**To reap from a file of URLs:**

```bash
python3 dir_reaper.py -f <file_with_urls>
```

**To specify the harvest location:**

```bash
python3 dir_reaper.py <url> -o <output_file>
```

If you forget the incantation, the Reaper will guide you:

```bash
python3 dir_reaper.py --help
```

## The Harvest

The reaped paths are saved to `results.txt` by default. Each line is a testament to a path found, a directory exposed.

## Disclaimer

With great power comes great responsibility. DirReaper is a tool for security research and ethical hacking. Do not use it for malicious purposes. The developer is not responsible for any misuse of this tool. The Reaper is a neutral force; its alignment is with the wielder. Use it wisely.
