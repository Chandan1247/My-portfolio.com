<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My_Portfolio </title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 text-gray-800">

    <!-- Navbar -->
    <header class="bg-gray-800 text-white p-4">
        <div class="container mx-auto flex justify-between items-center">
            <!-- Profile Photo and Name -->
        <div class="flex items-center space-x-4">
            <!-- Profile Image -->
            <img src="C:\Users\HP\OneDrive\Documents\Downloads\chand2.jpeg"                        class="w-14 h-14 rounded-full border-2 border-white-400">
            <h1 class="text-2xl font-bold">CHANDAN NP</h1>
            <nav>
                <a href="#about" class="mr-4 hover:text-blue-400">About</a>
                <a href="#Education" class="mr-4 hover:text-blue-400">Education</a>
                <a href="#projects" class="mr-4 hover:text-blue-400">Projects</a>
                <a href="#contact" class="hover:text-blue-400">Contact</a>
            </nav>
        </div>
    </header>
<!-- Navbar -->
<header class="bg-black-600 text-white p-4">
    <div class="container mx-auto flex items-center justify-between">  
        </div>

        <!-- Navigation Links -->
        
</header>
<!-- Display Image Section -->
<section id="display-image" class="bg-gray-100 py-12">
    <div class="container mx-auto px-6 text-center">
        <!-- Display Image -->
        <img src="C:\Users\HP\OneDrive\Documents\Downloads\st.jpg" alt="Description of the work" class="w-full max-w-xl mx-auto rounded-lg shadow-lg">
        <!-- Center-Aligned Text Section -->
<section class="bg-gray-100 py-12">
    <div class="container mx-auto px-6 text-center">
        <h2 class="text-3xl font-bold mb-4">Welcome to My Portfolio</h2>
        <p class="text-lg text-gray-700 mb-6">
            Here at My Coding Heaven, welcome!
            Here, ideas come to life when creativity and technology collide. As a software engineer, I'm committed to creating effective solutions and appreciating the elegance of code. Enter and explore the fascinating realm of software creation!
        </p>
        <a href="" class="bg-blue-500 text-white font-semibold py-2 px-4 rounded-md hover:bg-blue-600">
            View My Profile
        </a>
    </div>
</section>
    </div>
</section>

<!-- About Me Section -->
<section id="about" class="bg-white py-12">
    <div class="container mx-auto px-5">
        <h2 class="text-3xl font-bold text-leftside mb-5">About Me</h2>
        <p class="text-gray-700 text-lg leading-relaxed">
            As a driven MCA graduate, I have a solid background in software development. I have accumulated practical knowledge in Java development and other web technologies throughout the course of this year. I like coming up with effective answers and resolving challenging issues. 
            Exploring software frameworks, picking up new programming languages, and participating in open-source initiatives are some of my interests. In the world of technology, I'm constantly excited to learn new things and take on challenges.
        </p>
    </div>
</section>
    </section>
<!-- Education Section -->
<section id="education" class="bg-gray-100 py-12">
    <div class="container mx-auto px-6">
        <h2 class="text-3xl font-bold text-leftside mb-8">Education</h2>
        <!-- Education Item 1 -->
        <div class="bg-white shadow-md rounded-lg p-6 mb-6">
            <h3 class="text-xl font-semibold">Master of Computer Applications. (MCA) CGPA: 8.32</h3>
            <p class="text-gray-600"> Visvesvaraya Technological University(VTU), Bangalore</p>
            <p class="text-gray-500">2022 - 2024</p>
        </div>
        <!-- Education Item 2 -->
        <div class="bg-white shadow-md rounded-lg p-6 mb-6">
            <h3 class="text-xl font-semibold">Bachelor of Computer Applications. (BCA)</h3>
            <p class="text-gray-600">Kuvempu University Shanakaraghatta, Shivamogga</p>
            <p class="text-gray-500">2019 - 2022</p>
        </div>

        <!-- Add more education items as needed -->
    </div>
</section>
 <!-- Projects Section -->
<section id="projects" class="bg-white py-12">
    <div class="container mx-auto px-6">
        <h2 class="text-3xl font-bold text mb-8">Projects</h2>
        
        <!-- Project Grid -->
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            
            <!-- Project 1 -->
            <div class="bg-gray-100 rounded-lg shadow-lg p-6">
                <h3 class="text-xl font-semibold mb-2">1. Deepfake Detection Tweets Using Fast Text Embedding And Deep Learning.</h3>
                <p class="text-gray-700 mb-4">
                    A technique called "Deepfake Detection Tweets Using Fast Text Embedding and Deep Learning" can be used to spot deepfake content on social media. In order to more successfully identify false material, it employs deep learning techniques to identify suspect linguistic patterns in text analysis.
                </p>
                <p class="text-sm text-gray-600 mb-4"><b>Technologies used:</b> By using python for frontend, backend for Django-ORM, for designing HTML, CSS, javascript, for
                    database MYSQL(WAMP server).</p>
            </div>
            
            <!-- Project 2 -->
            <div class="bg-gray-100 rounded-lg shadow-lg p-6">
                <h3 class="text-xl font-semibold mb-2">2. Weather Data Analysis Using Machine Learning With Python.</h3>
                <p class="text-gray-700 mb-4">
                    "Weather Data Analysis Using Machine Learning with Python" describes how to use machine learning to analyze weather data in order to investigate weather patterns. By identifying patterns and trends in historical weather data, it assists in forecasting variables such as temperature, precipitation, and other climatic conditions.
                </p>
                <p class="text-sm text-gray-600 mb-4"><b>Technologies used:</b> The primary software components include data collecting libraries (such as Pandas and NumPy), data
                    visualization tools (such as Matplotlib and Seaborn), machine learning frameworks (such as TensorFlow),
                    and APIs for retrieving real-time meteorological data.</p>
            </div>
            
            <!-- Project 3 -->
            <div class="bg-gray-100 rounded-lg shadow-lg p-6">
                <h3 class="text-xl font-semibold mb-2">3. Alcohol Detection System, Arduino Uno Using IOT Devices.</h3>
                <p class="text-gray-700 mb-4">
                    A system known as a "Alcohol Detection System using Arduino Uno and IoT Devices" uses the internet to identify alcohol levels and send out alerts. It is helpful for workplace or vehicle safety checks since it detects alcohol in the air using sensors that are attached to an Arduino board.
                </p>
                <p class="text-sm text-gray-600 mb-4"><b>Technologies used:</b> The primary software components are sensor integration (’MQ-3 Alcohol Sensor’ for breath analysis) and
                    microcontroller programming (’Arduino IDE’).</p>
            </div>

             <!-- Project 4 -->
             <div class="bg-gray-100 rounded-lg shadow-lg p-6">
                <h3 class="text-xl font-semibold mb-2">4. Student Attendance System Using QR Code.</h3>
                <p class="text-gray-700 mb-4">
                    Students can check in using a "Student Attendance System Using QR Code" by scanning a special QR code. Compared to human roll calls, this technology is quicker and more precise because it registers attendance quickly.
                </p>
                <p class="text-sm text-gray-600 mb-4"><b>Technologies used:</b> By using java for frontend ,MYSQL for backend with Netbeans 8.2 Tools, student Attendance system QR
                    code has been developed.</p>
            </div>
        </div>
    </div>
    </section>
    <!-- Resume Preview Section -->
<section id="resume" class="bg-gray-100 py-12">
    <div class="container mx-auto px-6 text-center">
        <h2 class="text-3xl font-bold mb-3">Resume view</h2>
        
        <!-- Resume Preview Link -->
        <p class="text-gray-700 text-lg mb-4">
            Take a look at my experience, skills, and projects in detail.
        </p>
        <!-- Resume Link Button -->
        <a href="C:\Users\HP\OneDrive\Documents\Downloads\Chandan_NP_job_resume.pdf". target="_blank" class="inline-block bg-blue-500 text-white font-semibold py-3 px-6 rounded-md hover:bg-blue-600">
            View My Resume
        </a>
    </div>
</section>
    <!-- JavaScript -->
    <script src="script.js"></script>
    <!-- Footer -->
<footer class="bg-gray-600 text-white py-5">
    <div class="container mx-auto text-center">
    <!-- Contact Section -->
<section id="contact" class="bg-blue-200 py-12">
    <div class="container mx-auto px-6">
        <h2 class="text-black font-bold text-center mb-5">Contact Details</Details></h2>
        <!-- Contact Details -->
        <div class="text-center mb-2">
            <p class="text-lg text-gray-500">Email: <a href="mailto:Chandannp027@gmail.com.com" class="text-blue-500 hover:underline">Chandannp027@gmail.com.com</a></p>
            <p class="text-lg text-gray-500">Phone: <a href="tel:+91 8123619342" class="text-blue-500 hover:underline">+91 8123619342</a></p>
        </div>
    <!-- Footer -->
    <!-- JavaScript -->
    <script src="script.js"></script>
    <!-- Footer -->
<footer class="bg-gray-800 text-white py-6">
    <div class="container mx-auto text-center">
        <p class="text-lg font-bold mb-2"> Chandan_NP 2024</p>
        <!-- Social Media Links -->
        <div class="flex justify-center space-x-6 mb-4">
            <a href="https://www.linkedin.com/in/chandan-np-8573a7257" target="_blank" class="hover:text-yellow-400">
                <svg xmlns="https://www.linkedin.com/in/chandan-np-8573a7257" class="w-6 h-6 inline" fill="currentColor" viewBox="0 0 24 24"><path d="M19.998 0h-16c-2.21 0-4 1.79-4 4v16c0 2.21 1.79 4 4 4h16c2.21 0 4-1.79 4-4v-16c0-2.21-1.79-4-4-4zm-11 19h-3v-11h3v11zm-1.5-12.268c-.97 0-1.75-.787-1.75-1.755s.78-1.755 1.75-1.755c.97 0 1.75.787 1.75 1.755s-.78 1.755-1.75 1.755zm13.5 12.268h-3v-5.604c0-3.44-4-3.174-4 0v5.604h-3v-11h3v1.604c1.396-2.586 7-2.776 7 2.478v6.918z"/></svg>
            </a>
            <a href="mailto:Chandannp027@gmail.com" target="_blank" class="hover:text-yellow-400">
                <svg xmlns="Chandannp027@gmail.com" class="w-6 h-6 inline" fill="currentColor" viewBox="0 0 24 24"><path d="M12 12.713l-11.26-6.713 22.52 0-11.26 6.713zm-12-.713v11h24v-11l-12 7.07-12-7.07z"/></svg>
            </a>
            <a href="https://www.instagram.com/chandan_vishwakarma_07?igsh=cXljb2szem5pc2Jn&utm_source=qr" target="_blank" class="hover:text-yellow-400">
                <svg xmlns="https://www.instagram.com/chandan_vishwakarma_07?igsh=cXljb2szem5pc2Jn&utm_source=qr" class="w-6 h-6 inline" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 1.366.062 2.633.332 3.608 1.308.975.975 1.246 2.242 1.308 3.608.058 1.267.07 1.646.07 4.85s-.012 3.584-.07 4.85c-.062 1.366-.332 2.633-1.308 3.608-.975.975-2.242 1.246-3.608 1.308-1.267.058-1.646.07-4.85.07s-3.584-.012-4.85-.07c-1.366-.062-2.633-.332-3.608-1.308-.975-.975-1.246-2.242-1.308-3.608-.058-1.267-.07-1.646-.07-4.85s.012-3.584.07-4.85c.062-1.366.332-2.633 1.308-3.608.975-.975 2.242-1.246 3.608-1.308 1.267-.058 1.646-.07 4.85-.07zm0-2.163c-3.259 0-3.667.015-4.947.072-1.43.065-2.884.382-4.026 1.524-1.143 1.143-1.459 2.597-1.524 4.026-.057 1.28-.072 1.688-.072 4.947s.015 3.667.072 4.947c.065 1.43.382 2.884 1.524 4.026 1.143 1.143 2.597 1.459 4.026 1.524 1.28.057 1.688.072 4.947.072s3.667-.015 4.947-.072c1.43-.065 2.884-.382 4.026-1.524 1.143-1.143 1.459-2.597 1.524-4.026.057-1.28.072-1.688.072-4.947s-.015-3.667-.072-4.947c-.065-1.43-.382-2.884-1.524-4.026-1.143-1.143-2.597-1.459-4.026-1.524-1.28-.057-1.688-.072-4.947-.072zm0 5.838c-3.403 0-6.162 2.758-6.162 6.162s2.758 6.162 6.162 6.162 6.162-2.758 6.162-6.162-2.758-6.162-6.162-6.162zm0 10.324c-2.297 0-4.162-1.866-4.162-4.162s1.866-4.162 4.162-4.162 4.162 1.866 4.162 4.162-1.866 4.162-4.162 4.162zm6.406-11.845c-.796 0-1.443.646-1.443 1.443s.646 1.443 1.443 1.443 1.443-.646 1.443-1.443-.646-1.443-1.443-1.443z"/></svg>
            </a>
        </div>
        <p></p>
    </div>
</footer>
</body>
</html>
