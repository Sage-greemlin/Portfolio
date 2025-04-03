# Portfolio
My details 
## **📜 About Me Website - README**  

### **📌 Overview**  
This project is a **personal portfolio website** designed as an interactive chess-themed experience. Each chess piece represents different aspects of the creator's life. Users can interact with the pieces to learn more, and the King piece provides an option to **connect via Chess.com**.

---

## **🛠 Features**
### **🌟 Chess-Themed Navigation**
- The **King** represents a special interaction (Chess Play Invitation).
- The other **chess pieces (Queen, Rook, Bishop, Knight, Pawn)** reveal information about the creator's skills, work history, and interests.  

### **👆 Interactive Features**
- **Hover Effect**: Chess pieces enlarge when hovered over.  
- **Click Action**: Clicking a piece displays detailed information related to it.  
- **Auto-Close**: Displayed details automatically close after **3 seconds** if not hovered.  
- **Play Button**: Users can submit their email to receive the creator's Chess.com profile link.  

### **🔄 Smooth Navigation**
- Clicking on the **logo (top-left)** returns users to the homepage (`index.html`).  
- A separate **Contact Page** includes the creator’s profile picture and social links.  

---

## **📁 File Structure**
```
/about-me-website
│── index.html            # Main page with chess piece navigation
│── contact.html          # Contact page with profile & social links
│── styles.css            # Stylesheet for design & animations
│── script.js             # JavaScript for interactivity
│── store_email.php       # Backend script to store emails in MySQL
│── images/               # Folder containing chess piece images and profile picture
│── README.md             # This file (explaining the project)
```

---

## **💻 Technologies Used**
### **Frontend**
- **HTML5** for structure  
- **CSS3** for styling & animations  
- **JavaScript** for interactivity  

### **Backend**
- **PHP** (`store_email.php`) to handle form submissions  
- **MySQL** to store user emails  

---

## **📝 Setup & Installation**
1. **Download or Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/about-me-website.git
   cd about-me-website
   ```
2. **Run Locally**  
   Open `index.html` in a browser.  
3. **Backend Setup (Optional)**  
   - Install **PHP** and **MySQL**  
   - Create a database and table for emails  
   - Ensure `store_email.php` is correctly configured with your database details.  

---

## **📧 How the Chess Play Feature Works**
1. **User clicks "Play with Me"**  
2. **A form appears** prompting them to enter their email.  
3. **Once submitted,** the backend saves the email and **displays the Chess.com link**.  

---

## **🔗 Social & Contact Page**
- **Profile Picture** displayed instead of chess pieces.  
- **Links to social media** where the creator can be found.  
- **Mobile number** for direct contact.  

---

## **🚀 Future Improvements**
- Add animations when pieces move.  
- Improve accessibility and responsiveness.  
- Add more game-like interactions.  

---

## **🛠 Developer Notes**
- Ensure `store_email.php` has correct database credentials.  
- Keep images in the `/images/` folder for proper rendering.  
- For database setup, use the following MySQL table:
  ```sql
  CREATE TABLE emails (
      id INT AUTO_INCREMENT PRIMARY KEY,
      email VARCHAR(255) NOT NULL,
      submitted_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
  );
  ```

---

## **📜 License**
This project is for personal and educational use. Feel free to modify it!  

---

## **📩 Contact**
- **Email:** [patrickhood963@gmail.com]  
- **Chess.com Profile:** [GreemlinZh](https://www.chess.com/member/GreemlinZh)  
- **GitHub:** [Sage-greemlin]  

---
