# DuckChain Auto Farming Bot 
This bot will Quack or tap on the DuckChain telegram bot, support proxies and multi-account / multithread.

REGISTER ⨠ [DUCKCHAIN_BOT](https://t.me/DuckChain_bot/quack?startapp=p9wkJSBL)

### This bot helpfull?  Please support me by buying me a coffee: 
```
0xf86E74DB7AA1E535A7FD982f14ed84793a04a2c8 - EVM
```

## Features
- Auto Quack / Taps (ONLY)
- Multi Account / Threads Support
- Proxy Support
- Configurable via `config.json`

### Add configuration setting on `config.json` 

 **bool** : `true` or `false` | use_proxy  

  ```bash
{
    "use_proxy": false,
    "quack_delay": 0.4
}

  ```
### Add proxy account on `proxies.txt` 

  ```bash
username:password@proxy:port
  ```

## Prerequisites
Before installing and running this project, make sure you have the following prerequisites:
- Python 3.10+
- Other required dependencies

## Installation
1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/tyogiri12/Duckchain-Bot
    ```
2. Go to the project directory:
    ```bash
    cd Duckchain-Bot
    ```
3. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    pip install aiohttp
    pip install fake-useragent
    ```

## Usage
before starting the bot you must have your own initdata / queryid telegram! why query id? with query_id it is definitely more profitable because you don't have to bother changing your init data every time.

1. Use PC/Laptop or Use USB Debugging Phone
2. open the `DuckChain bot`
3. Inspect Element `(F12)` on the keyboard
4. at the top of the choose "`Application`" 
5. then select "`Session Storage`" 
6. Select the links "`DuckChain bot`" and "`tgWebAppData`"
7. Take the value part of "`tgWebAppData`"
8. take the part that looks like this: 

```txt 
query_id=xxxxxxxxx-Rxxxxuj&user=%7B%22id%22%3A1323733375%2C%22first_name%22%3A%22xxxx%22%2C%22last_name%22%3A%22%E7%9A%BF%20xxxxxx%22%2C%22username%22%3A%22xxxxx%22%2C%22language_code%22%3A%22id%22%2C%22allows_write_to_pm%22%3Atrue%7D&auth_date=xxxxx&hash=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```
9. add it to `data.txt` file or create it if you dont have one


You can add more and run the accounts in turn by entering a query id in new line like this:
```txt
query_id=xxxxxxx2xxx&hash=xxxxxx
query_id=xxxxxxx2xxx&hash=xxxxxx
```
## RUN THE BOT
after that run the DuckChain bot by writing the command

```bash
python main.py
```

## License
This project is licensed under the TELEGRAM CHANNEL(https://t.me/Deeplchain) | License.



