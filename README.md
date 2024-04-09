# Cow wisdom  - Accuknox

## Title: Containerisation and Deployment of Wisecow Application on Kubernetes 
Objective : To containerize and deploy the Wisecow application, hosted in the
above-mentioned GitHub repository, on a Kubernetes environment with secure TLS
communication.




- Create Docker file 
- Create Docker Image
- Deploy container on Kubernetes Environment
- Secure TLS communication
- 

## Getting Started

To run this project on your local machine, follow these steps:

1. **Prerequisites**

   ```bash
  sudo apt install fortune-mod cowsay -y
   ```

2. **Configure the Database:**

   Create a MySQL database and update the `application.properties` file with your database configuration:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```

3. **Build and Run the Application:**

   Use Maven to build and run the application:

   ```bash
   mvn spring-boot:run
   ```

4. **Access the Application:**

   Open your web browser and access the application at [http://localhost:8080](http://localhost:8080).

## Usage

- Take online assesment.
- Create random quizes.
- It help to check the knowledge about the topic


## Admin Login :

![Admin](Admin.png)

1. **Admin Home Page:**
   
![Admin Home](AdminHome.png)

3. **Question List:**
   
![Question List](QuestionList.png)

4. **Create Question:**
   
 ![Create Question](CreateQuestion.png)

5. **Quiz List:**
   
![Quiz List](QuizList.png)

6. **Create Quiz:**
   
![Create Quiz](CreateQuiz.png)

7. **User List:**
   
![User List](UserList.png)



## User Login :

![User Login](UserLogin.png)

1. **User Home:**
   
![User Home](UserrHome.png)

2. **Attempt Quiz List:**
   
   ![Attempt Quiz List](AtttemptQuizList.png)
   
3. **Attempting Quiz:**
   
![Attempt Quiz](AttemptingQuiz.png)

4. **Quiz Result:**

   ![Quiz Result](QuizResult.png)

## EER Diagram :
![EER](EER.png)



This project was created as a learning exercise and is based on tutorials and courses related to Spring Boot and web development.

---

Feel free to customize this README to provide more specific information about your project. Include any additional setup instructions, prerequisites, or specific details about your application that you think would be helpful for users.
