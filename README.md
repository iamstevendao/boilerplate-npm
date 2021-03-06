## Boilerplate App (Node.js)  
Original version generated by http://megaboilerplate.com

### Sample Apps: [url-shortener](https://iamsd-url-shortener.glitch.me/), [image-search-app](https://iamsd-images-search.glitch.me/), [email-sender-service](https://github.com/iamstevendao/email-sender-service)

## Highlights
- **Platform**: **node**
- **Framework**: **express**
- **Template Engine**: **Pug** 
- **CSS Framework**: **bootstrap**
- **CSS Preprocessor**: **less**
- **Build Tool**: npm
- **Database**: **mongodb**

## Configuration
1. Create a file name `.env` in the root folder.
2. Add API credentials to `.env`:
   ```bash
   # Mailgun configuration, should use session instead of password
   MAILGUN_USERNAME=''
   MAILGUN_PASSWORD=''
   # Session secret, can be a random string
   SESSION_SECRET=''
   # MongoDB connection URI
   MONGODB=''
   #Specified PORT number (optional, default value is 3000)
   PORT=''
   ```
3. Build and Run
   ```bash
   npm install && node server.js
   ```
4. Open `localhost:3000` in your browser.    
   (If you specified `PORT` in the `.env` file in the step 2, you would need to open `localhost:<YourPORT>`).
5. Enjoy!

### License
The [MIT License](https://github.com/sahat/megaboilerplate/blob/master/LICENSE) (MIT)

made with &#x2764; by [Steven](https://github.com/iamstevendao).
