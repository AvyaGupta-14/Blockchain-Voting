# Blockchain-Voting

Working Screenshot.
1. Add Candidate
   ![image](https://github.com/user-attachments/assets/40fcef8c-48fc-49c1-b3ed-75f3b7c19f04)
2.Candidate Added.
  ![image](https://github.com/user-attachments/assets/633c395e-9243-4379-bc20-99022a68d84f)
3. Regiter User
   ![image](https://github.com/user-attachments/assets/c2b2be4f-16c1-4b58-bdf9-a848da27e730)
4.Voting.
  ![image](https://github.com/user-attachments/assets/423462bb-45ae-49ac-9190-2b77fdbfd25a)
5.Voted.
  ![image](https://github.com/user-attachments/assets/d9c5775e-d430-4827-ba74-9afcd2c0cc1b)


# Connecting metamask and ganache
1.Open ganache and select show keys on any account. The show keys button is the key icon.
2.Copy the private key and click done.
3.Open the metamask menu which can be accessed by clicking the profile picture and select import account.
4.Paste the private key copied from ganache and click import.

# Cloning the project
git clone https://github.com/faizscripts/blockchain-voting-system

cd blockchain-voting-system

npm i

truffle compile

truffle migrateortruffle migrate --reset for subsequent runs

npm start

The project will open in the browser and metamask will ask you to select an account. Select the account we had imported earlier.
