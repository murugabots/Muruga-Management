# ᴇxᴏɴ ʀᴏʙᴏᴛ ᴇxᴀᴍᴘʟᴇ ᴘʟᴜɢɪɴ ғᴏʀᴍᴀᴛ

## ᴀᴅᴠᴀɴᴄᴇᴅ: ᴘʏʀᴏɢʀᴀᴍ
```ᴘʏᴛʏʜᴏɴ3

from pyrogram import filters
from Yone import pgram

# ᴀʟsᴏ ʏᴏᴜ ᴄᴀɴ ᴜsᴇ : pgram as pbot : any pyrogram client 

@pgram.on_message(filters.command("hi"))
async def hmm(_, message):
    await message.reply_text(
        "ʜɪɪɪɪ"
    )
    
__mod_name__ = "Hi"
__help__ = """
*ʜɪ*
- /hi: ʜɪɪɪ
"""
```

## ᴀᴅᴠᴀɴᴄᴇᴅ: ᴛᴇʟᴇᴛʜᴏɴ
```ᴘʏᴛʜᴏɴ3

from Yone import telethn
from Yone.events import register

@register(pattern="^/hi$")
async def _(event):
    j = "ᴋʏ ʀᴇ ʟᴏᴅᴇ"
    await event.reply(j)
    
__mod_name__ = "Hi"
__help__ = """
*Hi*
- /hi: ᴋʏ ʀᴇ ʟᴏᴅᴇ
"""
```

