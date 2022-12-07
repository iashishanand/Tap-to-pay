# Tap-to-pay

It is an Automatic Fare Collection System implemented by RFID/Smart card. The system consist of :-
1. NodeMCU – ESP8266
2. RFID Reader and RFID Cards – MFRC522
3. Google Sheet - Database

The program [Recharge.ino](https://github.com/iashishanand/Tap-to-pay/blob/main/Recharge.ino) will be used to recharge/write the balance of the RFID tags at the recharge booth, while [Tap-to-pay.ino](https://github.com/iashishanand/Tap-to-pay/blob/blob/main/Tap-to-pay.ino) will be deduct the fixed amount from the RFID tags and update the data in the google sheet when a customer enters the shuttle bus.

