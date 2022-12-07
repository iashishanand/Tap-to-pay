# Tap-to-pay

It is an Automatic Fare Collection System implemented by RFID/Smart card. The system consist of :-
1. NodeMCU – ESP8266
2. RFID Reader and RFID Cards – MFRC522
3. Google Sheet - Database

The program [Recharge.ino](../blob/main/Recharge.ino) will be used to recharge/write the balance of the RFID tags at the recharge booth, while [Tap-to-pay.ino](../blob/main/Tap-to-pay.ino) will be deduct the fixed amount from the RFID tags when a customers enter the shuttle bus.

