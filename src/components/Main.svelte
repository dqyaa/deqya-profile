<script>
    import Step from "./Step.svelte";

    let steps = [
        {
            name: "Online Cinema Booking",
            icon: "fa-solid fa-film",
        },
        {
            name: "HALMI Homestay",
            icon: "fa fa-home",
        },
        {
            name: "Online Wedding Boutique",
            icon: "fa-solid fa-crown",
        },
        {
            name: "Green House Temperature Control",
            icon: "fa-solid fa-diagram-project",
        },
        
        {
            name: "Weather Temperature Sensor",
            icon: "fa-solid fa-temperature-three-quarters",
        },
        {
            name: "UMT Merit MyStar",
            icon: "fa-solid fa-star",
        },
        {
            name: "Ship Detection From Remote Sensing Imagery",
            icon: "fa-solid fa-ship",
        },
        {
            name: "Brain Tumor Detection",
            icon: "fa-solid fa-brain",
        },
        {
            name: "Cashierless Checkout Store",
            icon: "fa-solid fa-basket-shopping",
        },
        {
            name: "Harbor Vision GIS",
            icon: "fa-solid fa-ship",
        },
        {
            name: "Novel PDF Summarizer",
            icon: "fa-solid fa-file-pdf",
        },
        {
            name: "Portfolio",
            icon: "fa fa-user",
        },
        
    ];

    let benefits = [
        {
            metric: "10x",
            name: "a fresh graduate",
            description:
                "As a fresh graduate in computer science with maritime informatics, I pursued my degree from October 2020 to January 2024. Despite my major, my passion for AI remains unwavering. I supplemented my education with AI courses like Image Processing as electives. ",
        },
        {
            name: "an AI enthusiast",
            description:
                "I am an AI enthusiast who dedicates my free time to research. My thirst for knowledge motivates me to stay updated with the latest technologies, essential in the fast-paced IT industry.",
        },
        {
            name: "a self taught developer",
            description:
                "Being a self-taught developer, I acquired coding skills beyond my university curriculum by leveraging various online platforms like Coursera, DataCamp, and YouTube. Currently, I'm delving deeper into 3D computer vision and MLOps, driven by my love for creative problem-solving.",
        },
         {
            metric: "10x",
            name: " a versatile team player",
            description:
                "As a proactive team member, I engage in volunteer work, currently involved in orphan care activities. Throughout my studies, I actively participated in committee clubs annually, honing not only my communication skills but also my leadership abilities. I thrive in collaborative environments, adept at working both as a team player and independently to achieve shared goals.",
        },
        {
            name: "also good in building website and mobile apps",
            description:
                "Not only am I proficient in machine learning, but I also excel in front-end development, back-end development, database management, and cybersecurity. I have undertaken numerous projects where I independently built entire systems, including websites, mobile applications, and machine learning models.",
        },
       
    ];
</script>

<main class="flex flex-col flex-1 p-4">
    <section
        id="introPage"
        class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14"
    >
        <div
            class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
        >
            <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
                Hi! I'm <span class="poppins text-violet-400">Deqya</span>
              
            </h2>
            <p class="text-xl sm:text-2xl md:text-3xl"> <!-- Increased text size -->
                Computer Science
                <span class="poppins text-violet-400">Fresh Grad</span>
            </p>

         
<div class="flex">
    <button onclick="location.href='mailto:aliyaalias19@gmail.com?subject=Job Offer for [Position Name] Position at [Company Name]'"
            class="blueShadow flex items-center mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950"
            style="margin-right: 5px;"
    >
        <div class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"></div>
        <h4 class="relative z-9">Hire Me</h4>
        <i class="fas fa-envelope ml-1"></i> <!-- Envelope Icon with reduced margin -->
    </button>

   <button onclick="window.location.href='/Resume deqya.pdf';"
        class="blueShadow flex items-center mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950"
        style="margin-left: 51px;"
>
    <div class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"></div>
    <h4 class="relative z-9">View Resume</h4>
    <i class="fas fa-download ml-1"></i> <!-- Download Icon with reduced margin -->
</button>
</div>




        </div>
        
       <div class="relative shadow-2xl grid place-items-center">
    <img
        src={"images/profile-me.png"}
        alt="Zetane Engine"
        class="object-cover z-[2] max-h-[80vh]" 
    />
</div>

        <!-- <div  class="flex p-0.5 relative max-w-[700px] w-full mx-auto">
            <div
                class="absolute inset-0 overflow-hidden rounded-md flex items-center justify-center"
            >
                <div
                    class="bg-gradient-to-r absolute inset-[-20px]  from-violet-800 to-indigo-800 specialSpin"
                />
            </div>

            <img
                src={"images/zetane-engine.jpeg"}
                alt="Zetane Engine"
                class="w-full h-full object-cover z-[2]"
            />
        </div> -->
    </section>
    <section class="py-20 lg:py-32 flex flex-col gap-24" id="projects">
        <div class="flex flex-col gap-2 text-center">
            <h6 class="text-large sm:text-xl md:text-2xl">
                A few of my creative endeavors.
            </h6>
            <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
                Curious to <span class="poppins text-violet-400">see</span> my work?
            </h3>
        </div>
       
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10">
            <Step step={steps[0]}>
                <p>
                    Developed an online cinema web application.
                </p>
                <p>
                    Collaborated with a team to create a user-friendly interface and a secure payment system for movie-goers.
                </p>
                <p> Technology used: <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Java</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">MySQL</span> 
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">REST API</span></p>
            </Step>
            <Step step={steps[1]}>
                <p>Met Mr. Halmi to gather requirements.</p>
                <p>Developed a web application for Mr. Halmi homestay.</p>
                <p>Collaborated with a team to create a user-friendly interface and a secure payment system for customers.</p>
                <p>Presented the final product to stakeholders.</p>
                <p> Technology used: <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Java</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">MySQL</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">REST API</span> </p>
            </Step>

            <Step step={steps[2]}>
                <p>Developed a web application for purchasing wedding dresses.</p>
                <p>Collaborated with a team to create a user-friendly interface and a secure payment system.</p> 
                <p> Technology used: <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Java</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">MySQL</span> 
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">MVC</span></p>
                 <p><span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">REST API</span></p>
            </Step>

             <Step step={steps[3]}>
                <p>Conducted research on optimizing greenhouse temperature control based on environmental factor.</p>
                <p>Developed a deep learning model to tackle the problem.</p> 
                <p>Built humidity and temperature sensor.</p>
                <p> Technology used: <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">ANFIS</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">MATLAB</span> 
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Arduino</span></p>
                 <p><span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">DHT11</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">REST API</span></p>
            </Step>

            <Step step={steps[4]}>
                <p>Developed a system for detecting weather conditions that can keep users updated via Telegram</p>
                <p>Analyzed temperature data to identify weather patterns and changes and collaborated with a team to design and implement the system.</p> 
                <p> Technology used: <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Python</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">DHT11</span> 
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Telegram</span></p>
                 <p><span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">FavorIOT</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">REST API</span></p>
            </Step>

            <Step step={steps[5]}>
                <p>Developed a web and mobile application for UMT HEPA staff and students as a final year project. </p>
                <p>Created a system that enables tracking of student attendance and access to campus facilities.</p> 
                <p>Designed intuitive user interfaces and efficient data management systems to enhance the user experience and streamline administrative processes </p>
                <p>Conducted testing and debugging to ensure that the system was fully functional and met all project objectives.</p> 
                <p> Technology used: <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">PHP</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Flutter</span> 
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">MySQL</span></p>
                 <p><span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Android Studio</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Arduino</span> 
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">REST API</span></p>
                 <p><span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">RFID sensor</span></p>
            </Step>

             <Step step={steps[6]}>
                <p>Developed and implemented a ship identification system using remote sensing images.</p>
                <p>Conducted comparative studies and real-world applications to validate the efficacy of the system in enhancing maritime surveillance.</p> 
                <p>Proposed and implemented various image processing methods, including image enhancement and segmentation, to enhance system performance.</p>
                <p> Technology used: <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">MATLAB</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Image processing</span> </p>
            </Step>

            <Step step={steps[7]}>
                <p>Applied Convolutional Neural Networks (CNN) to train the initial model, achieving substantial accuracy in brain tumor detection.</p>
                <p>Iteratively improved model performance by implementing a second CNN architecture, further refining the accuracy of the brain tumor detection system.</p> 
                <p>Innovated a human tracking model utilizing YOLOv8 and deepSORT, enabling real-time detection and tracking of customers within the store environment.</p>
                <p> Technology used: <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">CNN</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">VGG-16</span></p>
            </Step>
            
            <Step step={steps[8]}>
                <p>Developed and fine-tuned a high-precision product detection and tracking model, achieving an impressive accuracy of 97%.</p>
                <p>Designed and developed dedicated mobile apps catering to customers and a website interface tailored for store owners, facilitating seamless access to the deployed model.</p> 
                <p>Innovated a human tracking model utilizing YOLOv8 and deepSORT, enabling real-time detection and tracking of customers within the store environment.</p>
                <p> Technology used: <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Python</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">YOLOv8</span> 
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">DeepSORT</span></p>
                 <p><span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">OpenCV</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Roboflow</span> 
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Pandas</span></p>
                 <p><span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Facial Recognition</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Tensorflow</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Numpy</span></p>
                 <p><span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Flask</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">PostgreSQL</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">RestAPI</span></p>
                 <p><span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Android Studio</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Java</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Vysor</span></p>
            </Step>

             <Step step={steps[9]}>
                <p>Leveraged state-of-the-art techniques, including Mask R-CNN and instance segmentation, to achieve precise object segmentation, and classifying boats and pontoons in harbor and coastal imagery.</p>
                <p>Employed GeoPandas for seamless integration of spatial data, enabling efficient geographic information analysis.</p> 
                <p>Extracted objects attributes, including positions, azimuths, sizes, and lengths.</p>
                <p>Transformed segmented objects into GIS-compatible formats for seamless integration into mapping and navigation systems.</p>
                <p> Technology used: <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Python</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Mask R-CNN</span> </p>
                 <p><span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Segmentation</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Tensorflow</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">GeoPandas</span> 
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">GIS</span></p>
            </Step>

            <Step step={steps[10]}>
                <p>Extracted text from PDFs.</p>
                <p>Built a text summarizer to condense the extracted text.</p>
                <p>Implemented various NLP techniques including tokenization, stop word removal, lemmatization, and sentiment analysis to enhance summarization accuracy.</p>
                <p>Developed a website to allow user input and display the summarized text.</p>
                <p> Technology used: <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Python</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Flask</span> </p>
                 <p><span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">T5</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">BART</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">PyPDF</span> 
            </Step>

            <Step step={steps[11]}>
                <p>Created a website portfolio.</p>
                <p> Technology used: <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Svelte</span>
                 <span class="tag"style="display: inline-block; background-color: #8a3ffc; color: white; padding: 4px 8px; border-radius: 10px; font-size: 14px; margin-right: 5px;">Tailwind</span> </p>
            </Step>

        </div>
    </section>
    <section
        id="about"
        class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
    >
        <!-- <div class="z-[-1] bg-violet-950 w-screen left-1/2 -translate-x-1/2 top-0 h-full absolute"> </div> -->
        <div
            class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-violet-700 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-violet-700 py-4"
        >
            <h6 class="text-large sm:text-xl md:text-2xl">
                Want to know more?
            </h6>
            <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
                A bit <span class="poppins text-violet-400">about</span> me.
            </h3>
        </div>
        <p class="mx-auto poppins font-semibold text-lg sm:text-xl md:text-2xl">
            I am . . .
        </p>
        <div class="flex flex-col gap-20 w-full mx-auto max-w-[800px]">
            {#each benefits as benefit, index}
                <!-- <div class="flex flex-col gap-2 mx-auto">
                    <div class="flex items-end gap-4">
                        <p
                            class="poppins text-6xl sm:text-7xl md:text-8xl text-slate-500 font-medium"
                        >
                            {benefit.metric}
                        </p>
                        <p
                            class="text-xl sm:text-2xl md:text-3xl capitalize pb-2"
                        >
                            {benefit.name}
                        </p>
                    </div>
                    <p class="text-center italic">- {benefit.description}</p>
                </div> -->
                <div class="flex gap-6 sm:gap-8">
                    <p
                        class="poppins text-4xl sm:text-5xl md:text-6xl text-slate-500 font-semibold"
                    >
                        0{index + 1}
                    </p>
                    <div class="flex flex-col gap-6 sm:gap-8">
                        <h3 class="text-2xl sm:text-xl md:text-5xl">
                            {benefit.name}
                        </h3>
                        <p>{benefit.description}</p>
                    </div>
                </div>
            {/each}
        </div>
        <section class="py-20 lg:py-32 flex flex-col gap-24" id="skills">
        <div class="text-center">
    <h5 class="text-2xl sm:text-6xl font-semibold text-center poppins">
        My <span class="text-violet-400">Skills</span>
    </h5>
    <br>
    <p style="font-size: 14px; font-family: cursive;">
        Click on the logo/name to learn more
    </p>
</div>

      <!-- First row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.android.com/">
        <img src="images/android.png" alt="Android" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Android</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://angularjs.org/">
        <img src="images/angular js.png" alt="angularjs" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Angular JS</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.postman.com/what-is-an-api/">
        <img src="images/api.png" alt="api" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">API</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.arduino.cc/">
        <img src="images/arduino.jpg" alt="arduino" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Arduino</p>
    </a>
</div>
    </div>

    <!-- Second row -->
     <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://aws.amazon.com/">
    <div>
        <img src="images/aws.jpg" alt="aws" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold; center; display:">Amazon Web Services(AWS)</p>
        </div>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://azure.microsoft.com/en-us">
        <img src="images/azure.png" alt="azure" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Microsoft Azure</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://getbootstrap.com/">
        <img src="images/bootstrap.png" alt="bootstrap" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Bootstrap</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://en.wikipedia.org/wiki/The_C_Programming_Language">
        <img src="images/c.jpg" alt="c" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">C</p>
    </a>
</div>
    </div>

 <!-- third row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://en.wikipedia.org/wiki/C%2B%2B">
        <img src="images/c++.png" alt="c++" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">C++</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://codeigniter.com/">
        <img src="images/codeignitor.png" alt="codeignitor" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">CodeIgniter</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.w3schools.com/Css/">
        <img src="images/css.png" alt="css" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">CSS</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://developer.nvidia.com/cuda-toolkit">
        <img src="images/cuda.jpg" alt="cuda" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">CUDA</p>
    </a>
</div>
    </div>
     <!-- fourth row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://dart.dev/">
        <img src="images/dart.png" alt="dart" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Dart</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.djangoproject.com/">
        <img src="images/django.png" alt="django" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Django</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://fastapi.tiangolo.com/">
        <img src="images/fastapi.jpeg" alt="fastapi" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">FastAPI</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://firebase.google.com/">
        <img src="images/firebase.png" alt="firebase" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Firebase</p>
    </a>
</div>
    </div>

     <!-- fifth row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://flask.palletsprojects.com/en/3.0.x/">
        <img src="images/flask.jpg" alt="flask" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Flask</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://flutter.dev//">
        <img src="images/flutter.png" alt="flutter" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Flutter</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://cloud.google.com/free?utm_source=bing&utm_medium=cpc&utm_campaign=japac-MY-all-en-dr-bkws-all-all-trial-e-dr-1009882&utm_content=text-ad-none-none-DEV_c-CRE_-ADGP_Hybrid+%7C+BKWS+-+EXA+%7C+Txt+~+GCP+~+General_+Core+Brand-KWID_43700071932040193-kwd-75110656480739:loc-112-userloc_144194&utm_term=KW_google%20cloud%20platform-ST_google+cloud+platform&gclid=225354feda401574aea831331bbd2f6f&gclsrc=3p.ds&">
        <img src="images/gcp.png" alt="gcp" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Google Cloud Platform</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://git-scm.com/">
        <img src="images/git.png" alt="git" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Git</p>
    </a>
</div>
    </div>

     <!-- 6th row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://graphql.org/">
        <img src="images/graphql.png" alt="graphql" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">GraphQL</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.w3schools.com/html/">
        <img src="images/html.png" alt="html" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">HTML</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.java.com/en/">
        <img src="images/Java.png" alt="java" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Java</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.w3schools.com/js/DEFAULT.asp">
        <img src="images/JS.png" alt="js" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">JavaScript</p>
    </a>
</div>
    </div>

     <!-- 7th row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://keras.io/">
        <img src="images/Keras.png" alt="keras" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Keras</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://kotlinlang.org/">
        <img src="images/kotlin.png" alt="kotlin" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Kotlin</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://laravel.com/">
        <img src="images/laravel.png" alt="laravel" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Laravel</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.overleaf.com/home-2">
        <img src="images/latex.png" alt="latex" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Latex</p>
    </a>
</div>
    </div>

     <!-- 8th row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.geeksforgeeks.org/introduction-to-linux-operating-system/">
        <img src="images/linux.png" alt="linux" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Linux</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://matplotlib.org/">
        <img src="images/matplotlib.png" alt="matplotlib" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Matplotlib</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.mongodb.com/cloud/atlas/lp/try4?utm_source=bing&utm_campaign=search_bs_pl_evergreen_atlas_core_prosp-brand_gic-null_apac-my_ps-all_desktop_eng_lead&utm_term=mongodb&utm_medium=cpc_paid_search&utm_ad=e&utm_ad_campaign_id=415204527&adgroup=1222657400083678&msclkid=93d92672845d1dbf0e2e43bf40e758f5">
        <img src="images/mongodb.png" alt="mongodb" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">MongoDB</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.mysql.com/">
        <img src="images/mysql.png" alt="mysql" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">MySQL</p>
    </a>
</div>
    </div>

     <!-- 9th row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://nextjs.org/">
        <img src="images/next js.png" alt="nextjs" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Next JS</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://nodejs.org/en">
        <img src="images/node js.png" alt="nodejs" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Node JS</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://numpy.org/">
        <img src="images/numpy.jpg" alt="numpy" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">NumPY</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://opencv.org/">
        <img src="images/opencv.jpg" alt="opencv" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">OpenCV</p>
    </a>
</div>
    </div>

     <!-- 10th row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.oracle.com/in/">
        <img src="images/oracle.png" alt="oracle" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Oracle</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://pandas.pydata.org/">
        <img src="images/pandas.png" alt="pandas" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Pandas</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.php.net/">
        <img src="images/php.png" alt="php" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">PHP</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.postgresql.org/">
        <img src="images/postgres.jpg" alt="postgres" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">PostgreSQL</p>
    </a>
</div>
    </div>

     <!-- 11th row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.microsoft.com/en-us/power-platform/products/power-bi">
        <img src="images/power bi.jpg" alt="powerbi" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Power BI</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://docs.pytest.org/en/8.0.x/">
        <img src="images/pytest.png" alt="pytest" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Pytest</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.python.org/">
        <img src="images/python.png" alt="python" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Python</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://pytorch.org/">
        <img src="images/pytorch.png" alt="pytorch" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Pytorch</p>
    </a>
</div>
    </div>

     <!-- 12th row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://react.dev/">
        <img src="images/react.png" alt="react" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">React</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://aws.amazon.com/s3/">
        <img src="images/s3.png" alt="s3" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Amazon S3</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://scikit-learn.org/stable/index.html">
        <img src="images/scikit learn.jpg" alt="scikit-learn" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Scikit-learn</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://scipy.org/">
        <img src="images/sscipy.jpg" alt="sscipy" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">SciPy</p>
    </a>
</div>
    </div>

     <!-- 13th row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://spacy.io/">
        <img src="images/spacy.jpg" alt="spacy" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">SpaCy</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://spark.apache.org/">
        <img src="images/spark.jpg" alt="spark" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Apache Spark</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.w3schools.com/sql/">
        <img src="images/sql.jpg" alt="sql" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">SQL</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://svelte.dev/">
        <img src="images/svelte.png" alt="svelte" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Svelte</p>
    </a>
</div>
    </div>

     <!-- 14th row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.tableau.com/">
        <img src="images/tableu.png" alt="tableu" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Tableau</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.tensorflow.org/">
        <img src="images/tensorflow.png" alt="tensorflow" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Tensorflow</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.typescriptlang.org/">
        <img src="images/typescript.png" alt="typescript" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">TypeScript</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="hhttps://docs.python.org/3/library/unittest.html">
        <img src="images/unittest.png" alt="unittest" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Unittest</p>
    </a>
</div>
    </div>

     <!-- 15th row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://vuejs.org/">
        <img src="images/vue.jpg" alt="vue" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Vue Js</p>
    </a>
</div>
<div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.anaconda.com/">
        <img src="images/anaconda.jpg" alt="anaconda" class="rounded-full" style="width: 125px; height: 125px;">
        <p style="font-size: 20px; font-weight: bold;">Anaconda</p>
    </a>
</div>

    

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://deepai.org/machine-learning-glossary-and-terms/convolutional-neural-network">
        
        <p style="font-size: 20px; font-weight: bold;">CNN</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.freecodecamp.org/news/mask-r-cnn-explained-7f82bec890e3/">
        
        <p style="font-size: 20px; font-weight: bold;">Mask-RCNN</p>
    </a>
</div>
    </div>
     <!-- 16th row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://medium.com/analytics-vidhya/lstms-explained-a-complete-technically-accurate-conceptual-guide-with-keras-2a650327e8f2">
      
        <p style="font-size: 20px; font-weight: bold;">LSTM</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://learnopencv.com/understanding-multiple-object-tracking-using-deepsort/">
        
        <p style="font-size: 20px; font-weight: bold;">DeepSORT</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://medium.com/@curiositydeck/an-introduction-to-object-tracking-algorithms-a-beginners-guide-877771d3a9cf">
       
        <p style="font-size: 20px; font-weight: bold;">SORT</p>
    </a>
</div>


    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://www.geeksforgeeks.org/introduction-to-recurrent-neural-network/">
        
        <p style="font-size: 20px; font-weight: bold;">RNN</p>
    </a>
</div>
    </div>
<!-- 17th row -->  
        <div class="icons-container" style = "display: flex; flex-wrap: wrap; justify-content: center;">
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://huggingface.co/docs/transformers/model_doc/t5">
        
        <p style="font-size: 20px; font-weight: bold;">T5</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://huggingface.co/docs/transformers/model_doc/bart">
        
        <p style="font-size: 20px; font-weight: bold;">BART</p>
    </a>
</div>

    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://huggingface.co/docs/transformers/model_doc/openai-gpt">
       
        <p style="font-size: 20px; font-weight: bold;">OpenAI GPT</p>
    </a>

    </div>
    <div class="icon" style="margin: 10px; text-align: center; display: block; margin: 30px;">
    <a href="https://medium.com/analytics-vidhya/yolo-explained-5b6f4564f31">
        
        <p style="font-size: 20px; font-weight: bold;">YOLO</p>
    </a>
</div>
    </section>
</main>
