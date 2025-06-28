Project WebService-API-Adidas
This project is the Backend Web Service for the "Adidas-by-MUI" project. It is developed using Node.js, Express.js, and Axios. The backend connects to mock data stored in JSON format within the project's Backend folder and provides this data to be displayed on the frontend (Adidas-by-MUI).

How to Use
1. Open the Terminal and use the cd command to navigate to the Backend folder. Install the required npm packages: Express.js, Axios, and CORS, using the following commands:
csharp
Copy Edit
npm init -y
npm install express
npm install cors dotenv
npm install axios
2. Start the server using the command node server.js. Once running, you should see the message “Server is running on port 5000” in the Terminal, which indicates that the backend is working properly.

API Data Structure
1. id – Product ID
2. name – Product name
3. price – Actual selling price
4. originalPrice – Original (pre-discount) price
5. discount – Discount tag
6. clothing_sizes – Details of sizes and quantities, stored as an array containing:
- size – Size
- qty – Quantity
7. text-color – Color name of the product
8. color – Product color(s), stored as an array (for products with more than one color)
9. detail – Product details, stored as an array (used for displaying as a list)
10. category – Product category
11. img – Product images, stored as an array (for products with more than one image)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Project WebService-API-Adidas
Project นี้ Web Service Backend ของ Project Adidas-by-MUI พัฒนาด้วย Node JS, Express.js and axios โดยเชื่อมต่อข้อมูลจำลองรูปแบบ Json ใน Folder Backend ของ Project ดึงข้อมูลมาแสดงในส่วนของ Front end (Adidas-by-MU)

วิธีใช้งาน
1 เปิด Terminal และใช้คำสั่ง CD เข้าไป Folder Backend ติดตั้ง npm i ต่างๆ Express.js axios CORS
คำสั่ง
npm init -y
npm install express
npm install cors dotenv
npm install axios
2 ใช้งานได้ด้วยคำสั่ง node.server.js จะแสดงข้อความ “Server is running on port 5000” ที่ช่อง Terminal ก็จะถือว่าทำงานได้เรียบร้อยแล้ว

ประเภทข้อมูลใน API
1. id (Id สินค้า)
2. name (ชื่อสินค้า)
3. price (ราคาจริงที่วางขาย)
4. originalPrice (ราคาก่อนลดราคาสินค้า)
5. discount (Tag ลดราคา)
6. clothing_sizes (รายละเอียดขนาดและจำนวนสินค้า) เก็บข้อมูลรูปแบบ Array โดยด้านในจะมี
- size (ขนาด)
- qty (จำนวน)
7. text-color (ชื่อสีของสินค้า)
8. color (สีของสินค้า) เก็บข้อมูลรูปแบบ Array หากมีมากกว่า 1 สี
9. detail (รายละเอียดสินค้า) เก็บข้อมูลรูปแบบ Array เนื่องจากต้องการจัดวางเป็น List แยกบรรทัด
10. category (ประเภทสินค้า)
11. img (รูปภาพ) เก็บข้อมูลรูปแบบ Array เนื่องจาก Product มากกว่า 1 รูป
