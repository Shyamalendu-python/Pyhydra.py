# PyHydra Advanced 🐉

PyHydra is a high-performance, multi-threaded password cracker and authentication testing tool written in Python. It is designed to perform dictionary attacks against various network protocols to identify weak credentials. 

> ⚠️ **Disclaimer:** This tool is created strictly for **Educational Purposes** and authorized security testing. Do not use this tool on systems or networks you do not own or do not have explicit permission to test. The creator is not responsible for any misuse or damage.

---

## 🚀 Features

- **Multi-Protocol Support:** Crack FTP, SSH, HTTP, HTTP-GET, and MySQL authentication.
- **High Performance:** Utilizes Python's `ThreadPoolExecutor` for fast, concurrent multi-threading.
- **Memory Optimized:** Uses generators to load passwords on-the-fly, preventing RAM exhaustion even with massive wordlists.
- **Dynamic Progress Bar:** Clean, in-place real-time tracking of attempts, speed, and progress.
- **Graceful Shutdown:** Safely handles `Ctrl+C` without crashing active threads.
- **Modular Design:** Easy to extend and add new protocol modules.

---

## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone [https://github.com/Shyamalendu-python/PyHydra.py.git](https://github.com/Shyamalendu-python/PyHydra.py.git)
   
