# forward-telegram-chat
With this project, you can access telegram user and forward message from `A,B,C,D,E` to `F,G,H,I,J`.

## How to run this project
1. Clone this project.
`git clone link-project.git`
2. Open the project folder, and install requirement.
`pip3 install -r requirements.txt`
3. Open my.telegram.org to get your API_ID and API_HASH then use it in file `noise/write_chat_id.py` and `main.py`.
4. Run `python3 noise/write_chat_id.py`, input your phone number and login code. That file will print all your history chat with chat id, or you can open `chat_id_all.json` that just created.
5. Copy all chat_id that you want to `chat_id_receivers.json` and `chat_id.senders.json`.
6. Run `python3 main.py`, now all chat that come from senders will be forward to receivers.

## For the frontend version see this [repository](https://github.com/Hidayathamir/forward-telegram-chat-web).