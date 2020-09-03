# telegram-delete-all-messages
Delete all your messages in supergroups with python script.

## Quick Start
```
git clone https://github.com/borontov/telegram-delete-all-messages
cd telegram-delete-all-messages
pip install -r requirements.txt
python cleaner.py
```
## Obtain standalone telegram app API credentials
- Login to https://my.telegram.org/
- Select `API development tools` link
- Create standalone application
- Copy app_id and app_hash

## Usage
You need both App api_id and App api_hash to use script.

#### Environment variables
You could set API_ID and API_HASH environment variables to prevent entering API credentials manually.

#### Start
After starting script you will be prompted:
- To enter your Telegram APP credentials (if no environment variables found)
- Your account phone and then code sent to you by Telegram

#### Choosing supergroup
- After providing needed information you will get your supergroup dialogs
- Enter number found near desired supergroup title

#### Message removal process
- After choosing supergroup you would get informed about messages removal process
