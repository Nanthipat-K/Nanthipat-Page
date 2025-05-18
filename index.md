<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nanthipat Kongborrirak - Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f4f7f6; /* Light background */
            color: #333; /* Dark text */
            line-height: 1.6;
        }
        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 20px;
        }
        .section {
            background-color: #fff; /* White background for sections */
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px; /* Rounded corners */
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Subtle shadow */
        }
        .section-title {
            font-size: 1.8rem;
            font-weight: 700;
            margin-bottom: 15px;
            color: #0056b3; /* A shade of blue for titles */
        }
        .experience-item {
            margin-bottom: 20px;
            padding-bottom: 15px;
            border-bottom: 1px solid #eee; /* Separator line */
        }
        .experience-item:last-child {
            border-bottom: none;
        }
        .experience-title {
            font-size: 1.2rem;
            font-weight: 600;
            margin-bottom: 5px;
        }
        .experience-date {
            font-size: 0.9rem;
            color: #666;
            margin-bottom: 10px;
        }
        .skill-list {
            list-style: disc;
            margin-left: 20px;
        }
        .contact-info p {
            margin-bottom: 5px;
        }
        .link-button {
             display: inline-block;
             background-color: #007bff; /* Blue button */
             color: white;
             padding: 8px 15px;
             margin-top: 10px;
             border-radius: 5px;
             text-decoration: none;
             transition: background-color 0.3s ease;
        }
        .link-button:hover {
            background-color: #0056b3; /* Darker blue on hover */
        }
    </style>
</head>
<body>

    <div class="container">

        <header class="text-center py-8">
            <h1 class="text-4xl font-bold text-gray-800">Nanthipat Kongborrirak</h1>
            <p class="text-xl text-gray-600">Language and Technology Student</p>
        </header>

        <section class="section">
            <h2 class="section-title">About Me</h2>
            <p>
                Language and Technology student with a focus on Natural Language
                Processing and linguistics. Skilled in data acquisition, data analysis, and
                developing/evaluating NLP models. Successfully applied skills in
                projects involving sentiment transfer and comprehensive LLM
                performance assessment in Thai. Passionate about building innovative
                language technologies and ready to contribute to cutting-edge projects.
            </p>
        </section>

        <section class="section contact-info">
            <h2 class="section-title">Contact Information</h2>
            <p><strong>Phone:</strong> 083-771-9567</p>
            <p><strong>Email:</strong> nanthipat.ko@gmail.com</p>
            <p><strong>Address:</strong> 125/151 Kanchanapisek Rd, Bangkok 10250</p>
            </section>

        <section class="section">
            <h2 class="section-title">Education</h2>
            <div class="experience-item">
                <h3 class="experience-title">Language and Information Technologies, Faculty of Arts, Chulalongkorn University</h3>
                <p class="experience-date">2021-present</p>
            </div>
            <div class="experience-item">
                <h3 class="experience-title">French program, Triam Udom Suksa School</h3>
                <p class="experience-date">2017-2021</p>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Experience</h2>

            <div class="experience-item">
                <h3 class="experience-title">NLP Group Project</h3>
                <p class="experience-date">November 2023 – December 2023</p>
                <ul class="list-disc ml-5">
                    <li>Performed a 'neutral reframing' sentiment transfer task, converting negative Thai text to neutral.</li>
                    <li>Led dataset creation and annotation for Thai text sourced from free and social media platforms.</li>
                    <li>Fine-tuned multi-lingual models (mBart, mT5) pre-trained on Thai data using the mentioned dataset.</li>
                    <li>Applied augmentation via English-to-Thai translation to increase the size of dataset.</li>
                </ul>
                <p class="mt-3">
                    <a href="#" class="link-button">View Paper/Report (Placeholder)</a>
                    </p>
            </div>

            <div class="experience-item">
                <h3 class="experience-title">Motohashi Lab Internship</h3>
                <p class="experience-date">May 2024 – July 2024</p>
                <ul class="list-disc ml-5">
                    <li>Developed a system to extract and analyze patent and product information through web crawling.</li>
                    <li>Applied topic modeling techniques to identify key themes within the data.</li>
                    <li>Implemented a dual attention model to enhance the relationship mapping between textual data from patents and products.</li>
                    <li>Developed a recommendation system leveraging the insights from the dual attention model to suggest relevant products based on a given patent or vice versa.</li>
                </ul>
                <p class="mt-3">
                    <a href="#" class="link-button">View Paper/Report (Placeholder)</a>
                    </p>
            </div>

            <div class="experience-item">
                <h3 class="experience-title">Senior Project</h3>
                <p class="experience-date">January 2025 – April 2025</p>
                <ul class="list-disc ml-5">
                    <li>Evaluated the reading and comprehension proficiency of various Large Language Models (LLMs) in the Thai language, utilizing OpenRouter Al for API access to models and DSPy for experimenting different prompting strategies.</li>
                    <li>Benchmarked multilingual (GPT-40, Gemini Flash 2.0, DeepSeek V3) and Thai fine-tuned models (Typhoon2 8B, 70B) using Thai national exam datasets (A-Level, CU-TPT, O-NET).</li>
                    <li>Found that larger models achieved higher accuracy and few-shot prompting improved the performance especially smaller models. LLMs exceeded human average on less complex questions.</li>
                </ul>
                 <p class="mt-3">
                    <a href="#" class="link-button">View Paper/Report (Placeholder)</a>
                    </p>
            </div>

        </section>

        <section class="section">
            <h2 class="section-title">Skills</h2>
            <ul class="skill-list">
                <li>Python, HTML, and SQL</li>
                <li>Machine Learning</li>
                <li>LLMs and Prompt Engineering</li>
                <li>Natural Language Processing</li>
                <li>Linguistics</li>
                <li>Interpersonal/Communication skills</li>
            </ul>
        </section>

        <section class="section">
            <h2 class="section-title">Language</h2>
            <ul class="skill-list">
                <li>Thai (Native)</li>
                <li>English (TOEIC: 930)</li>
                <li>Japanese (Pre-Intermediate)</li>
                <li>French (A1)</li>
            </ul>
        </section>

        <section class="section">
            <h2 class="section-title">Relevant Courses</h2>
            <ul class="skill-list">
                <li>Basic Programming for Natural Language Processing</li>
                <li>Introduction to Computational Linguistics</li>
                <li>Natural Language Processing Systems</li>
                <li>Information System for The Humanities</li>
                <li>Database Management for The Humanities</li>
                <li>Introduction to Data Mining</li>
            </ul>
        </section>

    </div>

</body>
</html>
