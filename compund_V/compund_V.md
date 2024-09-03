# compund_V

1. Ran the file command, it was an executable, so ran it, and it asked for a password.

2. Decompiled the executable, but couldn't understand a single line of code, so gave it to ChatGPT, which gave the passcode for the executable. The executable returned a string of random characters. Not knowing to do, I tried base64 decoding but that didn't return anything. So I gave it back to ChatGPT which found a function named "decodeURL" in the executable's code, that was XOR'ing it with 9. So it ran it and gave me back a URL.

3. Opened the URL and there was Billy's "Don't be a Cunt" pic. Looked for subpages, found nothing. Then viewed the page source and found the flag.

