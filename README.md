### EXPERIMENT -07 CONFIGURING NETWORK SERVER FOR CONNECTING GATEWAY AND END NODE 
## NAME: DHANUSHA K
## REG NO: 212223040034
## Aim: 
To  configure the Network server and end device for transferring data on the network
## Components required: 
End node stm 32 development kit , Dragino LPS8, Network server 

## Theory :
When working with sensitive applications or files, saving progress on your local device is a start, but what if you lose access to your device? Network servers address this problem by hosting the files and programs most pertinent to the network and enabling access for consistent, real-time use. 

As a result, personnel or network clients can instantly access important data or tools while also facilitating collaboration between users. Multiple users can make changes to the same program or document for continued development over the course of a project. Via a secure login, remote users can connect to the home network.
![image](https://github.com/vasanthkumarch/EXPERIMENT-07-CONFIGURING-NETWORK-SERVER-FOR-CONNECTING-GATEWAY-AND-END-NODE-/assets/36288975/59db9b76-ddd5-4d6a-9075-8db233f5e479)


In the above graphic, the circle represents an organization network where a network server facilitates collaboration and file sharing between network clients (devices).

 The role of a network server, then, is to provide users with a set of services and access to resources on the network. These features include:

Permissioned access and log-ins for network users Gateway access to the Internet for an organization Centralized location for network resources  Shared access to devices on the network like a printer or a scanner Hosts multi-user apps like email servers, web applications, or CRM

## Procedure :

 1. login to the network server using login link  https://iot.saveetha.in/
 2. Click on the nework server as shown blow
    
 ![image](https://github.com/vasanthkumarch/EXPERIMENT-07-CONFIGURING-NETWORK-SERVER-FOR-CONNECTING-GATEWAY-AND-END-NODE-/assets/36288975/1bd434ca-1426-4102-8384-94473483543e)
 3. Click on the add gateway 
 
 ![image](https://github.com/vasanthkumarch/EXPERIMENT-07-CONFIGURING-NETWORK-SERVER-FOR-CONNECTING-GATEWAY-AND-END-NODE-/assets/36288975/47c2e08d-6598-4437-8b07-f213d6f3b8ac)
![image](https://github.com/vasanthkumarch/EXPERIMENT-07-CONFIGURING-NETWORK-SERVER-FOR-CONNECTING-GATEWAY-AND-END-NODE-/assets/36288975/e62ff028-99bc-485e-9808-fbb6e124f8b2)
![image](https://github.com/vasanthkumarch/EXPERIMENT-07-CONFIGURING-NETWORK-SERVER-FOR-CONNECTING-GATEWAY-AND-END-NODE-/assets/36288975/a2e3ae58-6402-49e8-8f96-679059c1842c)
4. Click on the lora options , lora - frequency plan 

5. Click on channels and create a new channel after which you can add a new end device
   
![image](https://github.com/vasanthkumarch/EXPERIMENT-07-CONFIGURING-NETWORK-SERVER-FOR-CONNECTING-GATEWAY-AND-END-NODE-/assets/36288975/1fb72be5-e48d-4cde-a329-0cfb0d29070f)

6. Add the attributes in the end device as  shown below 

 ![image](https://github.com/vasanthkumarch/EXPERIMENT-07-CONFIGURING-NETWORK-SERVER-FOR-CONNECTING-GATEWAY-AND-END-NODE-/assets/36288975/00bff30b-42fc-42d5-9540-285d270e41cb)
 
7.Using AT commands configure end device in serial port utility
AT Commands to set initially (Mandatory)
 AT+FDR // To do factory data reset
 AT+NJM=1 // To set OTAA mode
 AT+ADR=1 // To enable the ADR
 AT+TDC=600000 // To set the default sampling interval as 10 minutes
(Should not give below 5 minutes)
 AT+CLASS=C // To set class C
 AT+DEUI=XX XX XX XX XX XX XX XX // To set Device EUI key
 AT+APPEUI=XX XX XX XX XX XX XX XX // To set APP EUI key
 AT+APPEUI=XX XX XX XX XX XX XX XX XX XX XX XX XX XX XX XX //
To set APP Key
 ATZ // To take effective action on below settings (As like saving)



## OUTPUT 
<img width="1919" height="1013" alt="image" src="https://github.com/user-attachments/assets/18e83020-27b6-40f9-8c7a-8d6c5002f267" />

<img width="1919" height="972" alt="Screenshot 2025-12-01 090520" src="https://github.com/user-attachments/assets/87211660-0dc6-4bb3-978d-073901ff3719" />

<img width="1919" height="1078" alt="Screenshot 2025-12-01 090551" src="https://github.com/user-attachments/assets/e807cb9f-1215-415f-9604-301391736ea7" />

<img width="1919" height="970" alt="Screenshot 2025-12-01 090627" src="https://github.com/user-attachments/assets/47f45ef7-d342-4e3d-b1da-3a0165bfcd36" />

<img width="1919" height="1072" alt="Screenshot 2025-12-01 090641" src="https://github.com/user-attachments/assets/fa2f72cf-b149-4f4a-9953-bf74367000bc" />

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/d14fb0a7-a005-4cac-a66a-27a45dbf3c1a" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/90f931e5-2199-4906-bf23-3d7682ab05ed" />

<img width="1919" height="1070" alt="image" src="https://github.com/user-attachments/assets/e395d9b1-ce0d-4838-ab00-42e02d5a6838" />

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/73145a9c-e115-43e2-83b6-58fe451dde72" />

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/db9777d8-f356-4702-8619-3890122d46cc" />

<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/45626f64-3bd8-4d8d-a719-c8f0b16fc378" />


<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/dc4d49a6-4d15-42e2-b342-16b689d73c7a" />


<img width="1919" height="1076" alt="image" src="https://github.com/user-attachments/assets/3d057ac0-19c2-4534-a97e-764ff597ff25" />

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/14ee7d56-9010-46f9-8b50-a3e749f29626" />








## Result: 

  The Network server and end device for transferring data on the network has been accomplished.
