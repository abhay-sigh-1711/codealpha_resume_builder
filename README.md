# codealpha_resume_builder

Welcome to the Resume Builder project! This project is a web application that allows users to create professional resumes using a simple and intuitive interface. The application is built using HTML, CSS, and JavaScript, and it is hosted on AWS (Amazon Web Services).

## Features

- User-friendly interface: The resume builder provides a user-friendly interface that allows users to create, edit, and preview their resumes easily.
- Real-time editing: The application supports real-time editing, so you can see changes to your resume as you make them.
- Save and download: Once you're satisfied with your resume, you can save it and download it as a PDF file.

## How to Use

1. **Clone the repository:** Start by cloning this repository to your local machine using the following command:

```bash
git clone https://github.com/your-username/resume-builder.git
```

2. **Navigate to the project folder:** Change into the project directory using the `cd` command:

```bash
cd resume_builder
```

3. **Open index.html:** To use the application, simply open the `index.html` file in your web browser. The application should load, and you can start building your resume right away.

4. **Create your resume:** Fill in your personal details, work experience, education, skills, and any other relevant information in the provided fields. You can switch between different resume templates to see how your resume looks in different styles.

5. **Preview and download:** Once you've filled in all the necessary information, use the "Preview" feature to see how your resume will look when finalized. If you're satisfied, click the "Download" button to save your resume as a PDF file.

## Hosting on AWS

The application is currently hosted on AWS to ensure reliable and scalable access. It is deployed as a static website using Amazon S3 (Simple Storage Service). You can access the live application at the following URL:


http://resumebulider.s3-website-ap-northeast-1.amazonaws.com/


To host this project on your own AWS account, follow these steps:

1. Create an S3 bucket: Log in to your AWS account, navigate to the S3 service, and create a new bucket. Upload all the project files to this bucket.

2. Configure the bucket for static website hosting: In the S3 bucket settings, enable static website hosting and set the `index.html` as the default document.

3. Set permissions: Make sure the bucket and its contents have the necessary permissions to be publicly accessible.

4. Obtain the bucket URL: Once the bucket is configured for static website hosting, you will be provided with a URL. Use this URL to access the resume builder application on AWS.

## Contributions

We welcome contributions to this project. If you find any bugs, have suggestions for improvements, or want to add new features, feel free to create a pull request. Please make sure to follow the coding conventions and provide detailed information about the changes you propose.

## Contact

If you have any questions or need further assistance, feel free to contact me:

- Abhay Singh (abhay73abahy@gmail.com)

Thank you for using the Resume Builder project! We hope it helps you create impressive resumes with ease. Happy job hunting!
