# Outlook - Troubleshooting with the MFCMAPI Tool

Many a time, you run into an issue with an end user's Outlook. It won't start or you cannot see some rules.

We have used this tool many times where users have corrupt Inbox Rules which you cannot see in Outlook and have to use the tool to remove them.

You have a very powerful tool called MFCMAPI. This tool allows you to investigate Outlook issues.

***Warning !*** Do take note, this tool can change raw data so be careful what you modify or delete as it may be difficult to reverse. Rather work with someone that understands MAPI and Exchange to assist you with this.

## There are a few steps involved in running this tool:

You need to connect to your profile.
The views are different if you using cached vs online mode, namely: Cached mode will show "IPM_SUBTREE" and online mode will show "Top of Information Store"


## You can now perform a number of things on a profile using the MFCMAPI tool:

 - Save MAPI properties of an Item.
  
 - Check permissions on a folder.
  
 - Check Public Folders.
  
 - View .MSG or perform Conversions.
  
 - View Message Attachments.
  
 - Check rules in the Mailbox.
