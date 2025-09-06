!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MYT General services</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <!-- Header -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex items-center justify-between">
            <!-- Updated logo with SVG icon -->
            <a href="#" class="text-2xl font-bold text-blue-600 flex items-center gap-2">
                <svg class="h-10 w-10 text-blue-600" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 2L2 12h3.5v9h13v-9H22zm0 1.5L4.5 11h2.5v7.5h8.5V11h2.5zM15 10c0-1.1-.9-2-2-2s-2 .9-2 2 .9 2 2 2 2-.9 2-2zm-2.5 5.5v1.5h1.5v-1.5h-1.5zM8 15h1.5v1.5H8zm1.5-3.5h1.5v1.5H9.5zm2.5-1h1.5v1.5h-1.5zM9.5 8h1.5v1.5H9.5zm3.5 0h1.5v1.5h-1.5zm-3.5 5.5h1.5v1.5H9.5z" />
                </svg>
                <span>MYT General services</span>
            </a>
            <nav class="hidden md:flex space-x-6">
                <a href="#services" class="text-gray-600 hover:text-blue-600 font-medium transition duration-300">Services</a>
                <a href="#about" class="text-gray-600 hover:text-blue-600 font-medium transition duration-300">About</a>
                <a href="#portfolio" class="text-gray-600 hover:text-blue-600 font-medium transition duration-300">Portfolio</a>
                <a href="#contact" class="text-gray-600 hover:text-blue-600 font-medium transition duration-300">Contact</a>
            </nav>
            <button id="mobile-menu-button" class="md:hidden text-gray-600 hover:text-blue-600 focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </div>
    </header>

    <!-- Mobile Menu -->
    <div id="mobile-menu" class="hidden md:hidden bg-white shadow-md">
        <nav class="flex flex-col items-center py-4 space-y-4">
            <a href="#services" class="text-gray-600 hover:text-blue-600 font-medium transition duration-300">Services</a>
            <a href="#about" class="text-gray-600 hover:text-blue-600 font-medium transition duration-300">About</a>
            <a href="#portfolio" class="text-gray-600 hover:text-blue-600 font-medium transition duration-300">Portfolio</a>
            <a href="#contact" class="text-gray-600 hover:text-blue-600 font-medium transition duration-300">Contact</a>
        </nav>
    </div>

    <!-- Hero Section -->
    <section class="bg-blue-600 text-white py-12 md:py-24">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-3xl md:text-5xl font-bold mb-4 md:mb-6 leading-tight">Your Trusted Partner for All General Services</h1>
            <p class="text-lg md:text-xl mb-8 md:mb-12">Specializing in electrical, plumbing, CCTV, and ceiling work for residential and commercial clients.</p>
            <a href="#contact" class="bg-white text-blue-600 font-bold py-3 px-8 rounded-full shadow-lg hover:bg-gray-100 transition duration-300">Get a Free Quote</a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-12 md:py-20">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-10">Our Services</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service Card 1: Electrical -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <h3 class="text-xl font-semibold mb-2">Electrical Work</h3>
                    <p class="text-gray-600">Expert installation, repair, and maintenance for all residential and commercial electrical systems, ensuring safety and efficiency.</p>
                </div>
                <!-- Service Card 2: Plumbing -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <h3 class="text-xl font-semibold mb-2">Plumbing Services</h3>
                    <p class="text-gray-600">From leaky faucets and pipe repairs to fixture installations and maintenance, we handle all your plumbing needs with professional care.</p>
                </div>
                <!-- Service Card 3: CCTV -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <h3 class="text-xl font-semibold mb-2">CCTV & Security Systems</h3>
                    <p class="text-gray-600">We provide complete CCTV camera and security system installation, setup, and maintenance to keep your property safe and secure.</p>
                </div>
                <!-- Service Card 4: Ceiling -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <h3 class="text-xl font-semibold mb-2">Ceiling Installation & Repair</h3>
                    <p class="text-gray-600">Offering professional installation and repair of various ceiling types, including drywall and suspended ceilings, for a polished finish.</p>
                </div>
                <!-- Service Card 5: General Repairs -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <h3 class="text-xl font-semibold mb-2">General Home Repairs</h3>
                    <p class="text-gray-600">Need help with something else? We offer a wide range of general home repair services. Contact us with your project details!</p>
                 </div>
                 <!-- Service Card 6: Troubleshooting -->
                 <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <h3 class="text-xl font-semibold mb-2">Troubleshooting & Diagnosis</h3>
                    <p class="text-gray-600">Quickly and accurately diagnose and fix issues, from electrical faults to plumbing leaks, to restore functionality.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="bg-gray-200 py-12 md:py-20">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center gap-8">
            <div class="md:w-1/2">
                <img src="https://placehold.co/600x400/1e40af/ffffff?text=Professional+Services" alt="Professional services provider" class="rounded-lg shadow-lg w-full h-auto">
            </div>
            <div class="md:w-1/2">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">About MYT General services</h2>
                <p class="text-gray-700 leading-relaxed mb-4">
                    At MYT General services, we are dedicated to providing the highest quality work with a focus on safety and customer satisfaction. With years of experience, we handle a broad range of residential and commercial projects, from electrical and plumbing to CCTV and ceiling repairs.
                </p>
                <p class="text-gray-700 leading-relaxed">
                    We pride ourselves on our attention to detail, transparent pricing, and timely service. Your safety and satisfaction are our top priorities, and we ensure every job is completed to the highest standards.
                </p>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-12 md:py-20">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-10">Our Work</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
                <!-- IP Intercom Project Images -->
                <img src="1000020082.jpg" alt="Installing an IP intercom on a home wall" class="rounded-lg shadow-md w-full h-auto object-cover">
                <img src="1000020234.jpg" alt="A newly installed IP intercom outdoor unit" class="rounded-lg shadow-md w-full h-auto object-cover">
                <img src="1000020084.jpg" alt="The indoor IP intercom monitor showing a clear camera view" class="rounded-lg shadow-md w-full h-auto object-cover">
                <img src="1000020115.jpg" alt="The IP intercom monitor displaying a successful configuration message" class="rounded-lg shadow-md w-full h-auto object-cover">
                <!-- Remaining placeholders -->
                <img src="https://placehold.co/600x400/d1d5db/4b5563?text=Home+Renovation" alt="A general home renovation project" class="rounded-lg shadow-md w-full h-auto object-cover">
                <img src="https://placehold.co/600x400/d1d5db/4b5563?text=Troubleshooting+Fix" alt="A solved troubleshooting problem" class="rounded-lg shadow-md w-full h-auto object-cover">
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-blue-600 text-white py-12 md:py-20">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">Get in Touch</h2>
            <p class="text-lg md:text-xl mb-8">Ready for a reliable general contractor? Fill out the form below for a free estimate.</p>
            <div class="bg-white p-8 rounded-lg shadow-lg max-w-2xl mx-auto">
                <form id="contact-form" class="space-y-6">
                    <div>
                        <input type="text" id="name" name="name" placeholder="Your Name" class="w-full p-3 rounded-md border-gray-300 focus:ring-blue-500 focus:border-blue-500 text-gray-800" required>
                    </div>
                    <div>
                        <input type="email" id="email" name="email" placeholder="Your Email" class="w-full p-3 rounded-md border-gray-300 focus:ring-blue-500 focus:border-blue-500 text-gray-800" required>
                    </div>
                    <div>
                        <input type="tel" id="phone" name="phone" placeholder="Your Phone Number" class="w-full p-3 rounded-md border-gray-300 focus:ring-blue-500 focus:border-blue-500 text-gray-800">
                    </div>
                    <div>
                        <textarea id="message" name="message" rows="4" placeholder="Your Message" class="w-full p-3 rounded-md border-gray-300 focus:ring-blue-500 focus:border-blue-500 text-gray-800" required></textarea>
                    </div>
                    <button type="submit" class="w-full bg-blue-600 text-white font-bold py-3 px-6 rounded-md hover:bg-blue-700 transition duration-300">Send Message</button>
                </form>
                <div id="form-status" class="mt-4 text-sm font-medium text-green-600 hidden"></div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-gray-300 py-6">
        <div class="container mx-auto px-4 text-center">
            <p>&copy; 2024 MYT General services. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // Mobile menu functionality
        document.getElementById('mobile-menu-button').addEventListener('click', () => {
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenu.classList.toggle('hidden');
        });

        // Smooth scroll for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
                // Close mobile menu after clicking a link
                document.getElementById('mobile-menu').classList.add('hidden');
            });
        });

        // Handle contact form submission
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();

            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const phone = document.getElementById('phone').value;
            const message = document.getElementById('message').value;
            const statusMessage = document.getElementById('form-status');

            const subject = `New Inquiry from MYT General services Website - ${name}`;
            const body = `Name: ${name}\nEmail: ${email}\nPhone: ${phone}\n\nMessage:\n${message}`;
            const mailtoLink = `mailto:your.email@example.com?subject=${encodeURIComponent(subject)}&body=${encodeURIComponent(body)}`;

            window.location.href = mailtoLink;
            
            // Show success message
            statusMessage.textContent = 'Thank you for your message! We will get back to you shortly.';
            statusMessage.classList.remove('hidden', 'text-red-600');
            statusMessage.classList.add('text-green-600');
            
            // Clear form fields
            this.reset();
        });
    </script>

</body>
</html>
