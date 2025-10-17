
    Johnson Prototyping
    
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: #004aad;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        header img {
            max-width: 200px;
            height: auto;
        }
        nav {
            background: #f4f4f4;
            padding: 1rem;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }
        nav a {
            text-decoration: none;
            color: #004aad;
            font-weight: bold;
        }
        nav a:hover {
            color: #007bff;
        }
        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 2rem;
        }
        section {
            margin-bottom: 2rem;
        }
        h2 {
            color: #004aad;
        }
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
        }
        .service-item {
            background: #f9f9f9;
            padding: 1rem;
            border-radius: 5px;
            text-align: center;
        }
        footer {
            background: #004aad;
            color: white;
            text-align: center;
            padding: 1rem;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        @media (max-width: 600px) {
            nav ul {
                flex-direction: column;
                text-align: center;
            }
        }
    


    
        
        Innovative Solutions for Your Prototyping Needs
    
    
        
            Home
            Services
            About
            Contact
        
    
    
        
            Welcome to Johnson Prototyping
            We specialize in creating high-quality prototypes to bring your ideas to life. With years of experience and a commitment to excellence, we deliver solutions tailored to your needs.
        
        
            Our Services
            
                
                    Rapid Prototyping
                    Quickly turn your concepts into tangible prototypes using advanced techniques.
                
                
                    SLS 3D Printing with Nylon 12
                    High-precision Selective Laser Sintering (SLS) 3D printing using durable Nylon 12 for strong, functional prototypes.
                
                
                    Consulting
                    Expert guidance to refine your designs and optimize for production.
                
            
        
        
            About Us
            Johnson Prototyping is a family-owned business dedicated to innovation and quality. Founded in 2010, we have helped hundreds of clients across industries bring their ideas to market.
        
        
            Contact Us
            Email: [email protected]
            Phone: (555) 123-4567
            Address: 5900 Balcones Dr Ste 100, Austin, TX 78731
        
    
    
        © 2025 Johnson Prototyping. All rights reserved.
    
    
        // Smooth scroll for navigation links
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const section = document.querySelector(this.getAttribute('href'));
                section.scrollIntoView({ behavior: 'smooth' });
            });
        });
    
(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'99011011ef7b5283',t:'MTc2MDcxNzM5MS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();
