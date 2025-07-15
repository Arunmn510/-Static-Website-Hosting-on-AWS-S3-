This project shows how to host a static website on AWS S3.

## Features
- Static HTML/CSS website
- Public hosting on S3

## Prerequisites
- AWS account
- AWS CLI installed and configured

## Steps

1. **Create an S3 bucket**
   - Go to AWS S3 Console
   - Click “Create bucket”
   - Name your bucket (e.g., `my-website-bucket`)
   - Uncheck “Block all public access”

2. **Enable Static Website Hosting**
   - Go to your bucket > Properties
   - Enable “Static website hosting”
   - Specify `index.html` as index document

3. **Upload Files**
   - Upload `index.html` and `styles.css` from the `website/` folder
   - Set permissions to public (optional: use bucket policy)

4. **Get Website URL**
   - The bucket’s website endpoint will be shown under Static Website Hosting settings.

## Optional (Advanced)
- Use AWS CloudFront for CDN
- Add custom domain with Route 53

## License
MIT

5. website preview

   <img width="2880" height="1800" alt="Screenshot (81)" src="https://github.com/user-attachments/assets/5446ac24-6329-4d8d-9bea-23b8c1f5f2dd" />
