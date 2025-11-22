<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cardiovascular System</title>
    <style>
        /* CSS for the Presentation Layout and Basic Slide Transitions */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            overflow: hidden; /* Hide scrollbars */
            display: flex;
            flex-direction: column;
            height: 100vh;
            background-color: #f4f4f4;
        }

        #presentation-container {
            flex-grow: 1;
            position: relative;
            overflow: hidden;
        }

        .slide {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            display: none; /* Hidden by default */
            padding: 40px;
            box-sizing: border-box;
            background-color: white;
            transition: opacity 0.5s ease-in-out; /* Fade transition */
            opacity: 0;
            
            /* --- MODIFICATION HERE: 1fr (25%) for Content, 3fr (75%) for Media --- */
            display: grid;
            grid-template-columns: 1fr 3fr; 
            /* ------------------------------------------------------------------ */

            gap: 30px; /* Increased gap for better separation */
        }

        .slide.active {
            display: grid;
            opacity: 1;
        }

        .controls {
            padding: 10px;
            text-align: center;
            background-color: #333;
        }

        .controls button {
            padding: 10px 20px;
            margin: 0 10px;
            cursor: pointer;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
        }

        .content-area {
            text-align: left;
            overflow-y: auto; /* Allow scrolling if text is too long */
        }

        /* The media area ensures the content is centered and takes up available space */
        .media-area {
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden; /* Prevent media overflow */
            background-color: #eee; /* Light background for contrast */
        }

        /* --- MODIFICATION HERE: Ensure media fills the 3/4 area --- */
        .media-area img, 
        .media-area video,
        .media-area iframe {
            width: 100%;
            height: 100%;
            object-fit: contain; /* Scales content to fit, maintaining aspect ratio */
            max-width: 100%;
            max-height: 100%;
            display: block; /* Removes any default inline spacing */
            border: none; /* Remove placeholder border */
        }
        /* --------------------------------------------------------- */
    </style>
</head>
<body>

    <div id="presentation-container">
        
        <div class="slide active" data-narration="Welcome to this presentation on the Cardiovascular System. The cardiovascular system (CVS) consists of the heart and the blood vessels. The heart acts as a system of two pumps working in series and forms the driving force for blood flow.">
            <div class="content-area">
                <h2>❤️ The Cardiovascular System</h2>
                <p>The cardiovascular system (CVS) consists of the heart and the blood vessels.</p>
                <p>The heart acts as a system of two pumps working in series and forms the driving force for blood flow.</p>
                <p></p>
            </div>
            <div class="media-area">
				<img src="https://media.giphy.com/media/HkjGsgM6Ucyti/giphy.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="The blood vessels that take blood from the heart to various tissues are called arteries. The smallest arteries are called arterioles.">
            <div class="content-area">
                <h2>❤️ The Cardiovascular System</h2>
                <p>The blood vessels that take blood from the heart to various tissues are called arteries.</p>
                <p>The smallest arteries are called arterioles.</p>
                <p></p>
            </div>
            <div class="media-area">
				<img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExN3d4ZnN2c2wyZ2FhNXc0cDZsYzE0YnR0enNkdTR3MW0wcGxrcXNxYiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/tlOUJJxUIk608/giphy.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Arterioles open into a network of capillaries which constitute the microcirculation. The most important function of blood vessels, i.e. the rapid exchange of materials between the blood and extracellular fluid bathing the tissue cells is served by the capillaries. In other words, capillaries serve as the exchange region.">
            <div class="content-area">
                <h2>❤️ The Cardiovascular System</h2>
                <p>Arterioles open into a network of capillaries which constitute the microcirculation.</p>
                <p>The most important function of blood vessels, i.e. the rapid exchange of materials between the blood and extracellular fluid bathing the tissue cells is served by the capillaries.</p>
                <p>In other words, capillaries serve as the exchange region.</p>
            </div>
            <div class="media-area">
				<img src="https://th.bing.com/th/id/R.fc8b6ff4da568e43b231c3d803eeedd9?rik=s3xl2YwiTH22sg&riu=http%3a%2f%2fwww.dynamicscience.com.au%2ftester%2fsolutions1%2fbiology%2fcapillaries.gif&ehk=lWJTi5kOxNqb0gy01or3%2fpyaR%2bVs%2fhB%2f9B5EKgWdlaE%3d&risl=&pid=ImgRaw&r=0" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="In some situations capillaries are replaced by slightly different vessels called sinusoids. Blood from capillaries (or from sinusoids) is collected by small venules which join to form veins. Veins serve as the blood reservoir and return the collected blood to the heart.">
            <div class="content-area">
                <h2>❤️ The Cardiovascular System</h2>
                <p>In some situations capillaries are replaced by slightly different vessels called sinusoids.</p>
                <p>Blood from capillaries (or from sinusoids) is collected by small venules which join to form veins.</p>
                <p>Veins serve as the blood reservoir and return the collected blood to the heart.</p>
            </div>
            <div class="media-area">
				<img src="https://th.bing.com/th/id/R.b554b90ae6f1b1ca3a9938433eff42f4?rik=fKqBies%2fp7N1rw&riu=http%3a%2f%2fwww.dynamicscience.com.au%2ftester%2fsolutions1%2fbiology%2fcapanmtd.gif&ehk=mT6h5nyLTlXpe%2fk6AWYPD9kzTLv3YttaSjeyh4HVfi0%3d&risl=&pid=ImgRaw&r=0" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Primary functions of the CVS are: 1. Distribution of nutrients and oxygen (O2) to all body cells and 2. Collection of waste products and CO2 from different body cells, and to carry them to excretory organs for excretion.">
            <div class="content-area">
                <h2>FUNCTIONS OF CARDIOVASCULAR SYSTEM</h2>
				<h3>Primary functions of the CVS are:</h3>
                <p>1. Distribution of nutrients and oxygen (O2) to all body cells and</p>
                <p>2. Collection of waste products and CO2 from different body cells, and to carry them to excretory organs for excretion.</p>
                <p></p>
            </div>
            <div class="media-area">
				<img src="https://media.giphy.com/media/yoJC2ILrG0l7Rxar96/giphy.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Secondary functions that are subserved by the CVS are: 1. Thermoregulation, 2. Distribution of hormones to the target tissues and 3. Delivery of antibodies, platelets and leucocytes to aid body defence mechanism.">
            <div class="content-area">
                <h2>FUNCTIONS OF CARDIOVASCULAR SYSTEM</h2>
				<h3>Secondary functions that are subserved by the CVS are:</h3>
                <p>1. Thermoregulation,</p>
                <p>2. Distribution of hormones to the target tissues and</p>
                <p>3. Delivery of antibodies, platelets and leucocytes to aid body defence mechanism.</p>
            </div>
            <div class="media-area">
				<img src="https://i.pinimg.com/originals/1e/a5/61/1ea5611b28291125d1311c19809e8da8.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Physiology of CVS includes various aspects of physiology of heart as a pump and physiology of two main divisions of blood circulation—the pulmonary and systemic circulation.">
            <div class="content-area">
                <h2>PHYSIOLOGY OF CARDIOVASCULAR SYSTEM</h2>
				<h3></h3>
                <p>Physiology of CVS includes various aspects of physiology of heart as a pump and physiology of two main divisions of blood circulation—the pulmonary and systemic circulation.</p>
                <p></p>
                <p></p>
            </div>
            <div class="media-area">
				<img src="https://i.makeagif.com/media/5-21-2014/GUwiZq.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="The heart consists of two pumps in series (right and left halves) that are connected by pulmonary and systemic circulation.">
            <div class="content-area">
                <h2>PHYSIOLOGY OF CARDIOVASCULAR SYSTEM</h2>
				<h3></h3>
                <p>The heart consists of two pumps in series (right and left halves) that are connected by pulmonary and systemic circulation.</p>
                <p></p>
                <p></p>
            </div>
            <div class="media-area">
				<img src="https://orig00.deviantart.net/769b/f/2014/328/d/c/heart_beating_gif_by_sheereenabba-d87hty7.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="In systemic circulation the various systemic organs receive blood through parallel distribution channels.">
            <div class="content-area">
                <h2>PHYSIOLOGY OF CARDIOVASCULAR SYSTEM</h2>
				<h3></h3>
                <p>In systemic circulation the various systemic organs receive blood through parallel distribution channels.</p>
                <p></p>
                <p></p>
            </div>
            <div class="media-area">
				<img src="https://th.bing.com/th/id/R.43f57061d5ed1f4a79e615332f491fae?rik=lqXqBjgYbnVvHQ&riu=http%3a%2f%2fwww.artandsciencegraphics.com%2fwp-content%2fuploads%2fECMO-Flow.gif&ehk=bfiWT7FX2uSmtd1x5cevwC4pVsslYInpczH5AjoFiKY%3d&risl=&pid=ImgRaw&r=0" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="The parallel arrangement of vessels supply the body organs with blood of the same arterial composition (i.e. same O2 and CO2 tension, pH, glucose level) and essentially the same arterial pressure.">
            <div class="content-area">
                <h2>PHYSIOLOGY OF CARDIOVASCULAR SYSTEM</h2>
				<h3></h3>
                <p>The parallel arrangement of vessels supply the body organs with blood of the same arterial composition (i.e. same O2 and CO2 tension, pH, glucose level) and essentially the same arterial pressure.</p>
                <p></p>
                <p></p>
            </div>
            <div class="media-area">
				<img src="https://th.bing.com/th/id/R.43f57061d5ed1f4a79e615332f491fae?rik=lqXqBjgYbnVvHQ&riu=http%3a%2f%2fwww.artandsciencegraphics.com%2fwp-content%2fuploads%2fECMO-Flow.gif&ehk=bfiWT7FX2uSmtd1x5cevwC4pVsslYInpczH5AjoFiKY%3d&risl=&pid=ImgRaw&r=0" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Since the pulmonary and systemic circulation divisions are arranged in series, so both ventricles must pump the same amount of blood over any significant time period. Such a balanced output is achieved by an intrinsic property of cardiac muscle known as Frank–Starling mechanism.">
            <div class="content-area">
                <h2>PHYSIOLOGY OF CARDIOVASCULAR SYSTEM</h2>
				<h3></h3>
                <p>Since the pulmonary and systemic circulation divisions are arranged in series, so both ventricles must pump the same amount of blood over any significant time period.</p>
                <p>Such a balanced output is achieved by an intrinsic property of cardiac muscle known as Frank–Starling mechanism.</p>
                <p></p>
            </div>
            <div class="media-area">
				<img src="https://www.medgif.com/wp-content/uploads/2017/02/cfd3bd792366ce4d311a00b2406f76b6.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="The Frank-Starling mechanism describes how the heart's stroke volume increases in response to an increase in the volume of blood filling the ventricles, allowing the heart to adjust its output based on venous return.">
            <div class="content-area">
                <h2>PHYSIOLOGY OF CARDIOVASCULAR SYSTEM</h2>
				<h3></h3>
                <p>The Frank-Starling mechanism describes how the heart's stroke volume increases in response to an increase in the volume of blood filling the ventricles, allowing the heart to adjust its output based on venous return.</p>
                <p></p>
                <p></p>
            </div>
            <div class="media-area">
				<img src="https://media.tenor.com/dO9JYv5q8xsAAAAC/heart-heart-pumping.gif" alt=" ">
            </div>
        </div>

        <div class="slide" data-narration="This is the introductory lecture on cardiovascular system. This presentation is proudly created by Dr Khin Soe for dental students. Thanks for watching. See you next lecture.">
            <div class="content-area">
                <h2>📈Thanks for watching.</h2>
                <p></p>
                <p></p>
                <p></p>
            </div>
            <div class="media-area">
				<img src="https://usagif.com/wp-content/uploads/gifs/thanks-for-watching-20.gif" alt="">
            </div>
        </div>

        </div>

    <div class="controls">
        <button id="prev-btn" disabled>← Previous</button>
        <button id="tts-btn">▶ Play Narration</button>
        <button id="next-btn">Next →</button>
        <button id="fullscreen-btn">⤡ Fullscreen</button>
    </div>

    <script>
        const slides = document.querySelectorAll('.slide');
        const prevBtn = document.getElementById('prev-btn');
        const nextBtn = document.getElementById('next-btn');
        const ttsBtn = document.getElementById('tts-btn');
        const fullscreenBtn = document.getElementById('fullscreen-btn');
        let currentSlideIndex = 0;

        /**
         * Speech Synthesis (TTS) Functions
         */
        const synth = window.speechSynthesis;
        let utterance = null;
        let isSpeaking = false;

        function speakNarration(text) {
            if (synth.speaking) {
                synth.cancel();
            }

            // You can adjust voice properties here for better quality
            utterance = new SpeechSynthesisUtterance(text);
            utterance.lang = 'en-US';
            // Example of setting a faster rate and higher pitch (optional)
            // utterance.rate = 1.1; 
            // utterance.pitch = 1.0;

            utterance.onstart = () => {
                isSpeaking = true;
                ttsBtn.textContent = '⏸ Pause Narration';
            };

            utterance.onend = () => {
                isSpeaking = false;
                ttsBtn.textContent = '▶ Play Narration';
            };

            synth.speak(utterance);
        }

        function toggleSpeech() {
            if (synth.speaking && isSpeaking) {
                synth.pause();
                isSpeaking = false;
                ttsBtn.textContent = '▶ Resume Narration';
            } else if (synth.paused) {
                synth.resume();
                isSpeaking = true;
                ttsBtn.textContent = '⏸ Pause Narration';
            } else {
                const narrationText = slides[currentSlideIndex].getAttribute('data-narration');
                if (narrationText) {
                    speakNarration(narrationText);
                }
            }
        }

        ttsBtn.addEventListener('click', toggleSpeech);


        /**
         * Navigation Functions
         */
        function showSlide(index) {
            // Stop TTS when changing slides
            if (synth.speaking) {
                synth.cancel();
                isSpeaking = false;
                ttsBtn.textContent = '▶ Play Narration';
            }

            // Hide all slides
            slides.forEach(slide => {
                slide.classList.remove('active');
            });

            // Show the current slide
            if (slides[index]) {
                slides[index].classList.add('active');
                currentSlideIndex = index;
            }

            // Update button states
            prevBtn.disabled = currentSlideIndex === 0;
            nextBtn.disabled = currentSlideIndex === slides.length - 1;
        }

        function nextSlide() {
            if (currentSlideIndex < slides.length - 1) {
                showSlide(currentSlideIndex + 1);
            }
        }

        function prevSlide() {
            if (currentSlideIndex > 0) {
                showSlide(currentSlideIndex - 1);
            }
        }

        nextBtn.addEventListener('click', nextSlide);
        prevBtn.addEventListener('click', prevSlide);


        /**
         * Fullscreen Function
         */
        function toggleFullscreen() {
            const elem = document.documentElement; // Target the whole document

            if (!document.fullscreenElement) {
                if (elem.requestFullscreen) {
                    elem.requestFullscreen();
                } else if (elem.webkitRequestFullscreen) { /* Safari */
                    elem.webkitRequestFullscreen();
                } else if (elem.msRequestFullscreen) { /* IE11 */
                    elem.msRequestFullscreen();
                }
            } else {
                if (document.exitFullscreen) {
                    document.exitFullscreen();
                } else if (document.webkitExitFullscreen) { /* Safari */
                    document.webkitExitFullscreen();
                } else if (document.msExitFullscreen) { /* IE11 */
                    document.msExitFullscreen();
                }
            }
        }

        fullscreenBtn.addEventListener('click', toggleFullscreen);

        // Initial setup
        showSlide(currentSlideIndex);

    </script>
</body>
</html>
