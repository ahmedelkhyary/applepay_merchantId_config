### Apple pay integration with merchant id
<ol type="1">
  <li>Create MerchantId identifier </li>
  <li>Create apple payment processing certificate </li>
  <li>Create Merchant certificate </li>
  <li>verify website domain for web</li>
</ol>


#### Let's create MerchantId indentifier
- go to https://developer.apple.com
- login using your AppleID
- click Account - “Certificates, IDs & Profiles”
<br /> <img src="https://user-images.githubusercontent.com/70061912/236616256-6fd7158d-abf2-4b4e-8a18-1350e55285b3.png" height="300">
- In Certificates, Identifiers & Profiles, click Identifiers in the sidebar,
- then click the add button (+) on the top left.
- create a `Merchant IDs` identifier for your business
 <img src="https://user-images.githubusercontent.com/70061912/236620802-8dfe5e18-b3f7-4e27-a158-64f3aaadb133.png" height="300"> 
 
- select Merchant IDs, Press Continue
- enter description and identifier , Press Continue then Register

#### Let's create apple payment processing certificate
 - after register merchantId identifier
 - we need create apple payment processing certificate 
 - CREATE A PAYMENT PROCESSING CERTIFICATE TO ENCRYPT PAYMENT INFORMATION
 
 <img src="https://user-images.githubusercontent.com/70061912/236620902-5a6e6ebf-6b9a-468c-9d94-d87281acf633.png" height="300">

 - select your merchant IDs
 - select no and continue  
 - select processing file from your PC location 
 
 <img src="https://user-images.githubusercontent.com/70061912/236621009-09938294-38c4-44e0-aad0-e6e2fd79ac5c.png" height="300">
 
- apple pay payment processing certificate created
- download certificate
 
#### Let's create Merchant Certificate
  - create apple pay merchant identity certificate
  - select your merchant IDs
 
  <img src="https://user-images.githubusercontent.com/70061912/236621188-9526c866-f4f5-4a58-8248-cf9acf6a02ab.png" height="300">

  - add Merchant file , from your PC location 
  - select continue , download cretificate  

   <img src="https://user-images.githubusercontent.com/70061912/236621289-8ab04881-ffed-45ea-b865-f7fa4c04f38f.png" height="300">

#### Let's verify Merchant domain
 - add url domain 
 - URL OF WEBSITE LIKE WWW.EXAMPLE.COM
 
  <img src="https://user-images.githubusercontent.com/70061912/236619543-eafec214-02f2-4889-a634-bcf1e8e4f03f.png" height="300">

 - download this file , and select copy url link below and send it to Backend team to add into server
 - after Backend team added this file , Press ok to verify 

  <img src="https://user-images.githubusercontent.com/70061912/236619613-a6f37f9f-86fa-4547-9fbc-a51252545344.png" height="300">
  
### IOS SETUP
 - Runner 
 - Signing & Capabilities
 - (+) capabiltiy
 - select apple pay
 - select merchant IDs 

  <img src="https://user-images.githubusercontent.com/70061912/236619994-deeb14d5-1969-449a-8c44-9cd090eac8fe.png" height="300">





 
 
 

