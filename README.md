During the bootcamp, the following are the details of what i carried out and the images as evidence.

# ALEO WORKSHOP 1 
## Deployment Link: https://explorer.aleo.org/transaction/at1nzdvqt4v4fyujkyhpv48d7hw0gc3t6teynk3g7y9z6z8kn8qp5psz4ev28
### Deployment ID: at1nzdvqt4v4fyujkyhpv48d7hw0gc3t6teynk3g7y9z6z8kn8qp5psz4ev28
#### Description of Steps Used
For my second_leo, I wrote the following code accordingly:
- leo new my_second_leo: This was to create my project named my_second_leo
- cd my_second_leo: To change directory to current working directory
- Changed the private key in the .env file to the private key in my leo wallet
- leo run 2u32 3u32 --network testnet: This was to add the two numbers which gave us 5u32. u32 is the datatype
- leo deploy --network testnet: This made it possible for us to see the changes/activities on our leo wallet.
i fee was deducted from the aleo wallet.

##### Screenshot
![Screenshot (913)](https://github.com/user-attachments/assets/4662df35-7ef2-4e13-94f7-7ffe2d7f939b)

# ALEO WORKSHOP 2
## Deployment Link: https://explorer.aleo.org/transaction/at1uq2shxcwcl5nz0f5jgzcr9ncfcweq7tv8tudze8ufrrg4ep3xsxqmkh25t
### Deployment ID: at1uq2shxcwcl5nz0f5jgzcr9ncfcweq7tv8tudze8ufrrg4ep3xsxqmkh25t
#### Description of Steps Used
For my leo_project_token, I Wrote the codes using the following
- ../ to go to the previous directory
- leo_new_project_token: to create a new project with the name project token.
- cd project_token: To change directory to current working directory
- Changed the private key in the .env file to the private key in my leo wallet
- leo run mint <my_aleo_address> <amount>u64; e.g leo run mint aleo1fgftssyjrxh58gcw5ngnre7ttp6s5h9h70l93ltlkmmdmza58yxsdctefv 100u64, that is what i used.
- leo run transfer "<Token_Record>" <to_address> <amount>u64
- We were  able to use the generated record from 1st command to input into the second command's first input and then our to address and amount
- leo deploy --network testnet
- a gas of 7 credits was charged.

##### Screenshot
![Screenshot (919)](https://github.com/user-attachments/assets/dd319383-ec3d-43da-8103-0c24f7697f0a)
![Screenshot (920)](https://github.com/user-attachments/assets/4e061ce2-d692-4b72-b017-ae5acbedf17e)

# ALEO WORKSHOP 3
## Deployment Link: https://explorer.aleo.org/transaction/at1uc522zjljnvvfhq0jn95swsngzreakylnwu597npuwt3vm5cvg9s7qr457
### Deployment ID: at1uc522zjljnvvfhq0jn95swsngzreakylnwu597npuwt3vm5cvg9s7qr457
#### Description of Steps Used
For my aleo_voice_2, I Wrote the codes using the following
- ../ to go to the previous directory
- cd my_project_name: To change directory to current working directory
- Changed the private key in the .env file to the private key in my leo wallet
- leo run combine_hash_owner_receiver my leo wallet address receivers leo wallet address;
- example: leo run combine_hash_owner_receiver aleo1fgftssyjrxh58gcw5ngnre7ttp6s5h9h70l93ltlkmmdmza58yxsdctefv aleo1ce7wf7chgd5cywajg589z7mv433t8ua26h6dslfmgw2jgj02hvrs6qp8cm
- leo deploy --network testnet

##### Screenshot
![Screenshot (921)](https://github.com/user-attachments/assets/49bf9565-b317-428f-bb67-e87bfcff49e0)
![Screenshot (922)](https://github.com/user-attachments/assets/9c20c86f-2572-4d4f-8d6c-4bdea94b99a7)

#Wallet Screenshots
![Screenshot (938)](https://github.com/user-attachments/assets/1995355a-685b-47b2-9147-32994eb78e24)
![Screenshot (939)](https://github.com/user-attachments/assets/145fd186-3bff-430f-a69c-18572ec788f3)

