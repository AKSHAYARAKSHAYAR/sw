

<!doctype html>

<html lang="en">

  <head>

    <meta charset="UTF-8" />

    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <link

      rel="shortcut icon"

      href="/static/image/favicon.png"

      type="image/x-icon"

    />



    <meta name="msapplication-TileColor" content="#ffaa00ff" />

    <meta name="theme-color" content="#ffaa00ff" />



    <!-- Google tag (gtag.js) -->

    <script

      async

      src="https://www.googletagmanager.com/gtag/js?id=G-F6894KZX3J"

    ></script>

    <script>

      window.dataLayer = window.dataLayer || [];

      function gtag() {

        dataLayer.push(arguments);

      }

      gtag("js", new Date());



      gtag("config", "G-F6894KZX3J");

    </script>



    <!-- FB OG and Twitter head part -->

    



<!-- Start headtag -->

<meta

  name="keywords"

  content="Python Course, Cyber Security Course, Ethical Hacking Course, Internet of Things Course, Diploma Project, IEEE Projects"

/>

<meta name="author" content="Skill Disk" />



<meta

  name="description"

  content="Excel your skills with Realtime Projects @SkillDisk "

/>

<meta property="og:type" content="website" />

<meta

  property="og:title"

  content="Programming and Ethical Hacking Courses  @SkillDisk | Friend for your skill development."

/>

<meta property="og:description" content="" />

<meta

  property="og:url"

  content="https://skilldisk.com/"

/>

<meta property="og:site_name" content="www.skilldisk.com" />

<meta

  property="og:image"

  content="https://skilldisk.com/static/image/head/home_head.png"

/>

<meta property="og:image:width" content="1200" />

<meta property="og:image:height" content="630" />



<meta name="twitter:card" content="summary" />

<meta

  name="twitter:description"

  content="Excel your skills with Realtime Projects @SkillDisk "

/>

<meta

  name="twitter:title"

  content="Programming and Ethical Hacking Courses @SkillDisk | Friend for your skill development."

/>

<meta name="twitter:site" content="@skilldisk" />

<meta

  name="twitter:image"

  content="https://skilldisk.com/static/image/head/home_head.png"

/>

<meta name="twitter:creator" content="@skilldisk" />





<!-- End headtag -->





    <!-- Snippets -->

    

<title>

  SkillDisk | Cyber Security | Python Course | Projects | Internship

</title>





    <!-- Css Files -->

    

<!-- Java script file for theme variable retrieving -->

<script src="/static/js/darktheme_var.js"></script>



<link rel="stylesheet" href="/static/css/style.min.css" />





    <!-- Extra Css -->

     

  </head>

  <body class="min-h-screen bg-gray-100 dark:bg-gray-900">

    <!-- Navigation -->

    

<nav>

  <div class="container flex flex-wrap justify-between items-center mx-auto">

    <a href="/" class="flex z-50">

      <img

        class="h-6 md:h-8"

        src="/static/image/logo.png"

        alt="Skill Disk Logo"

      />

    </a>



    <div class="flex items-center md:order-2">

      <div

        x-data="{open:false}"

        @mouseover="open=true"

        @mouseleave="open=false"

      >

        <!-- Darkmode button -->

        <button

          data-tooltip-target="dark-theme-tooltip"

          id="theme-toggle"

          type="button"

          class="rounded-lg text-sm p-2.5 group bg-neutral-200 dark:bg-neutral-700"

        >

          <svg

            id="theme-toggle-dark-icon"

            class="w-5 h-5 hidden transform group-hover:-rotate-45 bg-transparent transition duration-300"

            fill="none"

            stroke="currentColor"

            viewBox="0 0 24 24"

            xmlns="http://www.w3.org/2000/svg"

          >

            <path

              stroke-linecap="round"

              stroke-linejoin="round"

              stroke-width="2"

              d="M20.354 15.354A9 9 0 018.646 3.646 9.003 9.003 0 0012 21a9.003 9.003 0 008.354-5.646z"

            ></path>

          </svg>

          <svg

            id="theme-toggle-light-icon"

            class="w-5 h-5 hidden transform group-hover:rotate-45 bg-transparent transition duration-300"

            fill="currentColor"

            viewBox="0 0 20 20"

            xmlns="http://www.w3.org/2000/svg"

          >

            <path

              d="M10 2a1 1 0 011 1v1a1 1 0 11-2 0V3a1 1 0 011-1zm4 8a4 4 0 11-8 0 4 4 0 018 0zm-.464 4.95l.707.707a1 1 0 001.414-1.414l-.707-.707a1 1 0 00-1.414 1.414zm2.12-10.607a1 1 0 010 1.414l-.706.707a1 1 0 11-1.414-1.414l.707-.707a1 1 0 011.414 0zM17 11a1 1 0 100-2h-1a1 1 0 100 2h1zm-7 4a1 1 0 011 1v1a1 1 0 11-2 0v-1a1 1 0 011-1zM5.05 6.464A1 1 0 106.465 5.05l-.708-.707a1 1 0 00-1.414 1.414l.707.707zm1.414 8.486l-.707.707a1 1 0 01-1.414-1.414l.707-.707a1 1 0 011.414 1.414zM4 11a1 1 0 100-2H3a1 1 0 000 2h1z"

            ></path>

          </svg>

        </button>

        <div

          id="dark-theme-tooltip"

          x-show="open"

          class="top-16 right-5 hidden md:block absolute z-10 py-2 px-3 text-sm bg-neutral-300 rounded-lg dark:bg-neutral-700"

        >

          Toggle DarkMode

          <div class="tooltip-arrow" data-popper-arrow></div>

        </div>

      </div>

      <div x-data="{open:false}">

        <button

          @click="open=! open"

          class="inline-flex z-50 items-center p-2 ml-1 text-sm rounded-lg md:hidden"

        >

          <svg

            x-show="!open"

            class="w-6 h-6"

            fill="currentColor"

            viewBox="0 0 20 20"

            xmlns="http://www.w3.org/2000/svg"

          >

            <path

              fill-rule="evenodd"

              d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"

              clip-rule="evenodd"

            ></path>

          </svg>

          <svg

            x-show="open"

            class="w-6 h-6 z-50"

            fill="currentColor"

            viewBox="0 0 20 20"

            xmlns="http://www.w3.org/2000/svg"

          >

            <path

              fill-rule="evenodd"

              d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"

              clip-rule="evenodd"

            ></path>

          </svg>

        </button>

        <!-- Mobile Navigation Bar -->

        <div

          x-show="open"

          x-transition:enter="transition ease-out duration-300"

          x-transition:enter-start="opacity-0 scale-50"

          x-transition:enter-end="opacity-100 scale-100"

          x-transition:leave="transition ease-in duration-300"

          x-transition:leave-start="opacity-100 scale-100"

          x-transition:leave-end="opacity-0 scale-50"

          class="absolute top-0 left-0 min-w-full h-screen bg-gray-100 dark:bg-gray-900 z-40"

        >

          <ul class="flex flex-col h-screen justify-center items-center">

            <li class="p-4 uppercase">

              <a href="/" aria-current="page">Home</a>

            </li>

            <li class="p-4 uppercase nav-li-active">

              <a href="/about/">About</a>

            </li>

            <li class="p-4 uppercase nav-li-active">

              <a href="/course/">Course</a>

            </li>

            <li class="p-4 uppercase">

              <a href="/project/">Project</a>

            </li>

            <li class="p-4 uppercase">

              <a href="/webinar/">Webinar</a>

            </li>

            <li class="p-4 uppercase">

              <a href="/contact/">Contact</a>

            </li>

          </ul>

        </div>

      </div>

    </div>



    <div

      class="hidden justify-between items-center w-full md:flex md:w-auto md:order-1"

    >

      <div

        class="flex flex-col mt-4 md:flex-row md:space-x-8 md:mt-0 md:text-sm"

      >

        <div>

          <a

            href="/"

            class="nav-li nav-li-active"

            aria-current="page"

          >

            Home

          </a>

        </div>



        <div>

          <a href="/about/" class="nav-li">About</a>

        </div>



        <div>

          <a href="/course/" class="nav-li">Course</a>

        </div>



        <div

          class="cursor-pointer"

          x-data="{projectshow : false}"

          @click="projectshow= !projectshow"

          @mouseleave="projectshow=false"

        >

          <div @mouseover="projectshow=true" class="flex items-center nav-li">

            <div>

              <a class="nav-li" href="/project/">Project</a>

            </div>

            <svg

              xmlns="http://www.w3.org/2000/svg"

              class="h-4 w-4"

              :class="{'rotate-180': projectshow, 'rotate-0': !projectshow}"

              fill="none"

              viewBox="0 0 24 24"

              stroke="currentColor"

              stroke-width="1"

            >

              <path

                stroke-linecap="round"

                stroke-linejoin="round"

                d="M19 9l-7 7-7-7"

              />

            </svg>

          </div>

          <div

            x-show="projectshow"

            class="absolute top-10 left-0 min-h-max min-w-full bg-gray-100 dark:bg-gray-900"

          >

            <div class="md:p-5 md:px-10 lg:p-10 lg:px-20">

              <div class="grid grid-cols-3 gap-2">

                <div class="border-r-2">

                  <h2

                    class="text-center text-primary-dark dark:text-primary cursor-default"

                  >

                    Program

                  </h2>

                  <ul class="project-link">

                    <li>

                      <a href="#">

                        <svg

                          xmlns="http://www.w3.org/2000/svg"

                          class="h-5 w-5"

                          viewBox="0 0 20 20"

                          fill="currentColor"

                        >

                          <path

                            fill-rule="evenodd"

                            d="M3 5a2 2 0 012-2h10a2 2 0 012 2v8a2 2 0 01-2 2h-2.22l.123.489.804.804A1 1 0 0113 18H7a1 1 0 01-.707-1.707l.804-.804L7.22 15H5a2 2 0 01-2-2V5zm5.771 7H5V5h10v7H8.771z"

                            clip-rule="evenodd"

                          />

                        </svg>

                        Computer Science Engineering

                      </a>

                    </li>

                    <li>

                      <a href="#">

                        <svg

                          xmlns="http://www.w3.org/2000/svg"

                          class="h-5 w-5"

                          viewBox="0 0 20 20"

                          fill="currentColor"

                        >

                          <path

                            fill-rule="evenodd"

                            d="M11.3 1.046A1 1 0 0112 2v5h4a1 1 0 01.82 1.573l-7 10A1 1 0 018 18v-5H4a1 1 0 01-.82-1.573l7-10a1 1 0 011.12-.38z"

                            clip-rule="evenodd"

                          />

                        </svg>

                        Electrical & Electronics Engineering

                      </a>

                    </li>

                    <li>

                      <a href="#">

                        <svg

                          xmlns="http://www.w3.org/2000/svg"

                          class="h-5 w-5"

                          viewBox="0 0 20 20"

                          fill="currentColor"

                        >

                          <path d="M13 7H7v6h6V7z" />

                          <path

                            fill-rule="evenodd"

                            d="M7 2a1 1 0 012 0v1h2V2a1 1 0 112 0v1h2a2 2 0 012 2v2h1a1 1 0 110 2h-1v2h1a1 1 0 110 2h-1v2a2 2 0 01-2 2h-2v1a1 1 0 11-2 0v-1H9v1a1 1 0 11-2 0v-1H5a2 2 0 01-2-2v-2H2a1 1 0 110-2h1V9H2a1 1 0 010-2h1V5a2 2 0 012-2h2V2zM5 5h10v10H5V5z"

                            clip-rule="evenodd"

                          />

                        </svg>

                        Electronics & Communication Engineering

                      </a>

                    </li>

                  </ul>

                </div>



                <div class="border-r-2">

                  <h2

                    class="text-center text-primary-dark dark:text-primary cursor-default"

                  >

                    Topics

                  </h2>

                  <ul class="project-link grid grid-cols-2">

                    <li><a href="#">Python. </a></li>

                    <li><a href="#">Internet of Things. </a></li>

                    <li><a href="#">Embedded System. </a></li>

                    <li><a href="#">Raspberry-Pi. </a></li>

                    <li><a href="#">Power Electronics. </a></li>

                    <li><a href="#">Cyber Security </a></li>

                  </ul>

                </div>



                <div class="flex flex-col justify-between text-center">

                  <h2

                    class="ltext-center text-primary-dark dark:text-primary cursor-default"

                  >

                    Key Words

                  </h2>

                  <div class="flex flex-wrap place-content-center">

                    <a href="#" class="chip">Arduino</a>

                    <a href="#" class="chip">Raspberry pi pico</a>

                    <a href="#" class="chip">8051</a>

                    <a href="#" class="chip">IOT</a>

                    <a href="#" class="chip">Power Electronics</a>

                    <a href="#" class="chip">Cyber Security</a>

                    <a href="#" class="chip">Mobile App</a>

                    <a href="#" class="chip">Web Application</a>

                    <a href="#" class="chip">Hacking</a>

                  </div>

                </div>

              </div>

            </div>

          </div>

        </div>

        <div>

          <a href="/webinar/" class="nav-li">Webinar</a>

        </div>

        <div>

          <a href="/contact/" class="nav-li">Contact</a>

        </div>

      </div>

    </div>

  </div>

</nav>





    <!-- Banner -->

    



<div class="grid content-center text-center min-h-[75vh] md:min-h-[80vh]">

  <h1>Welcome to <span class="text-primary font-nova">Skill Disk</span></h1>

  <h2>Excel your skills with Realtime Projects</h2>

  <br />

  <br />

  <p class="text-base px-3 md:px-8">

    We work relentlessly to achieve our

    <span

      class="underline decoration-secondary dark:decoration-tertiary decoration-wavy"

    >

      <a href="#!">Vision</a>

    </span>

    and help students to learn better through industrial projects and our 4A

    model.

  </p>

  <br />

  <p>

    <a href="/project/" class="btn-outline">Projects</a>

    <a href="/course/" class="btn">Courses</a>

  </p>

</div>





    <!-- content -->

    



<!-- Courses -->

<div class="mobile-container">

  <div class="min-h-[75vh]">

    <div class="text-center content-center">

      <h2>Choose the Course That Fits your Career Goals</h2>

      <hr class="sd-line" />

      <br />

      <h2 class="text-4xl">Courses</h2>

    </div>



    <div

  class="p-4 md:px-8 grid grid-col-1 sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-4 gap-5"

>

  

  <div class="ind-card">

    <img

      class="block dark:hidden"

      src="/media/CourseModel/images/Python_Advanced.png"

      alt="Python Advanced - skill disk"

    />

    <img

      class="hidden dark:block"

      src="/media/CourseModel/images/Python_Advanced_9AqscNf.png"

      alt="Python Advanced - skill disk"

    />



    <h2 class="text-2xl text-secondary-light dark:text-tertiary">

      Python Advanced

    </h2>

    <h3 class="text-gray-700 dark:text-gray-400">

      Duration: <span>72+ Hrs</span>

    </h3>

    <h3 class="text-gray-700 dark:text-gray-400">

      Code: <span>SDC23PY002</span>

    </h3>

    <br />

    <h3 class="text-center">

      <a href="/course/python-advanced/" class="btn block w-full">

        View Course

      </a>

    </h3>

  </div>



  

  <div class="ind-card">

    <img

      class="block dark:hidden"

      src="/media/CourseModel/images/Ethical_Hacking_and_Penetration_Testing.png"

      alt="Ethical Hacking and Penetration Testing - skill disk"

    />

    <img

      class="hidden dark:block"

      src="/media/CourseModel/images/Ethical_Hacking_and_Penetration_Testing_BUmSCez.png"

      alt="Ethical Hacking and Penetration Testing - skill disk"

    />



    <h2 class="text-2xl text-secondary-light dark:text-tertiary">

      Ethical Hacking and Penetration Testing

    </h2>

    <h3 class="text-gray-700 dark:text-gray-400">

      Duration: <span>90+ Hrs</span>

    </h3>

    <h3 class="text-gray-700 dark:text-gray-400">

      Code: <span>SDC23CS002</span>

    </h3>

    <br />

    <h3 class="text-center">

      <a href="/course/ethical-hacking-and-penetration-testing/" class="btn block w-full">

        View Course

      </a>

    </h3>

  </div>



  

  <div class="ind-card">

    <img

      class="block dark:hidden"

      src="/media/CourseModel/images/Django_Full_Stack_Web_Development.png"

      alt="Django Full Stack Web Development - skill disk"

    />

    <img

      class="hidden dark:block"

      src="/media/CourseModel/images/Django_Full_Stack_Web_Development_CwPXNrZ.png"

      alt="Django Full Stack Web Development - skill disk"

    />



    <h2 class="text-2xl text-secondary-light dark:text-tertiary">

      Django Full Stack Web Development

    </h2>

    <h3 class="text-gray-700 dark:text-gray-400">

      Duration: <span>80+ Hrs</span>

    </h3>

    <h3 class="text-gray-700 dark:text-gray-400">

      Code: <span>SDC23WD02</span>

    </h3>

    <br />

    <h3 class="text-center">

      <a href="/course/django-full-stack-web-development/" class="btn block w-full">

        View Course

      </a>

    </h3>

  </div>



  

  <div class="ind-card">

    <img

      class="block dark:hidden"

      src="/media/CourseModel/images/Internet_of_Things_Foundation.png"

      alt="Internet of Things Foundation - skill disk"

    />

    <img

      class="hidden dark:block"

      src="/media/CourseModel/images/Internet_of_Things_Foundation_cd57HK9.png"

      alt="Internet of Things Foundation - skill disk"

    />



    <h2 class="text-2xl text-secondary-light dark:text-tertiary">

      Internet of Things Foundation

    </h2>

    <h3 class="text-gray-700 dark:text-gray-400">

      Duration: <span>75+ Hrs</span>

    </h3>

    <h3 class="text-gray-700 dark:text-gray-400">

      Code: <span>SDC23IT001</span>

    </h3>

    <br />

    <h3 class="text-center">

      <a href="/course/internet-of-things-foundation/" class="btn block w-full">

        View Course

      </a>

    </h3>

  </div>



  

</div>



    <div class="text-center">

      <a href="/course/" class="btn-outline text-xl"

        >All Courses</a

      >

    </div>

  </div>

</div>

<br />

<div class="page-brakes">

  <div class="m-2 px-2 text-center">

    <h2>

      Have you given a thought over,<br />

      “What do I aspire? How do I fulfil my aspirational goals?”

    </h2>

    <br />

    <h3 class="">Check out our 4-A model towards success.</h3>

    <br />

    <a href="/about/#sd_model" class="btn">Read Now</a>

  </div>

</div>

<br />

<!-- Projects -->

<div class="mobile-container mt-10">

  <div class="min-h-[75vh]">

    <div class="text-center content-center">

      <h2>Dont just ₹ buy the project. Get Trained @SkillDisk</h2>

      <hr class="sd-line" />

      <br />

      <h2 class="text-4xl">Projects</h2>

    </div>



    

<div

  class="p-4 md:px-8 grid grid-col-1 sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-4 gap-5"

>

  <div class="ind-card">

    <img

      class="block dark:hidden"

      src="/static/image/project/iot_light.png"

      alt="Internet of Things Projects @ skill disk"

    />

    <img

      class="hidden dark:block"

      src="/static/image/project/iot_dark.png"

      alt="Internet of Things Projects @ skill disk"

    />



    <h2 class="text-2xl text-secondary-light dark:text-tertiary">

      Internet of Things

    </h2>

  </div>



  <div class="ind-card">

    <img

      class="block dark:hidden"

      src="/static/image/project/webapplication_light.png"

      alt="Cloud Application Projects @ skill disk"

    />

    <img

      class="hidden dark:block"

      src="/static/image/project/webapplication_dark.png"

      alt="Cloud Application Projects @ skill disk"

    />



    <h2 class="text-2xl text-secondary-light dark:text-tertiary">

      Cloud Applications

    </h2>

  </div>



  <div class="ind-card">

    <img

      class="block dark:hidden"

      src="/static/image/project/embeddedsystem_light.png"

      alt="Embedded System Projects"

    />

    <img

      class="hidden dark:block"

      src="/static/image/project/embeddedsystem_dark.png"

      alt="Embedded System Projects"

    />



    <h2 class="text-2xl text-secondary-light dark:text-tertiary">

      Electrical and Electronics Projects

    </h2>

  </div>



  <div class="ind-card">

    <img

      class="block dark:hidden"

      src="/static/image/project/python_light.png"

      alt="Embedded System Projects"

    />

    <img

      class="hidden dark:block"

      src="/static/image/project/python_dark.png"

      alt="Embedded System Projects"

    />



    <h2 class="text-2xl text-secondary-light dark:text-tertiary">

      Python & Raspberry pi

    </h2>

  </div>

</div>



    <div class="text-center">

      <a href="/project/" class="btn-outline text-xl"

        >Explore More</a

      >

    </div>

  </div>

</div>



<br />





    <!-- footer -->

    



<footer>

  <div class="footer-main">

    <div>

      <p class="lg:max-w-[500px] text-justify text-sm leading-relaxed">

        <span class="text-4xl font-nova text-primary">Skill Disk</span> is

        fastest growing online and offline education base situated in the

        Silicon Valley of India. Our courses and syllabus are designed with view

        of present and future market trends. We work relentlessly to achieve our

        vision and help students to learn better through industrial projects and

        our 4A model.

      </p>

    </div>



    <div class="footer-imp-links flex-grow-0">

      <h2>Important Links</h2>

      <ul class="p-2">

        <li>

          <a href="/"> Home </a>

        </li>

        <li>

          <a href="/about/"> About </a>

        </li>

        <li>

          <a href="/course/"> Courses </a>

        </li>

        <li>

          <a href="/project/"> Project </a>

        </li>

      </ul>

    </div>



    <div class="flex-grow">

      <h2 class="text-center">Stay Connected</h2>

      <div class="p-2 flex gap-2 justify-center">

        <!-- Facebook -->

<a href="https://www.facebook.com/skilldisk" target="_blank">

  <svg

    class="w-8 h-8 fill-[#1877F2] hover:fill-primary"

    xmlns="http://www.w3.org/2000/svg"

    viewBox="0 0 24 24"

  >

    <path

      d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"

    />

  </svg>

</a>



<!-- Instagram -->

<a href="https://www.instagram.com/skill_disk/" target="_blank">

  <svg

    xmlns="http://www.w3.org/2000/svg"

    viewBox="0 0 30 30"

    class="w-8 h-8 fill-[#E1306C] hover:fill-primary"

  >

    <path

      d="M 9.9980469 3 C 6.1390469 3 3 6.1419531 3 10.001953 L 3 20.001953 C 3 23.860953 6.1419531 27 10.001953 27 L 20.001953 27 C 23.860953 27 27 23.858047 27 19.998047 L 27 9.9980469 C 27 6.1390469 23.858047 3 19.998047 3 L 9.9980469 3 z M 22 7 C 22.552 7 23 7.448 23 8 C 23 8.552 22.552 9 22 9 C 21.448 9 21 8.552 21 8 C 21 7.448 21.448 7 22 7 z M 15 9 C 18.309 9 21 11.691 21 15 C 21 18.309 18.309 21 15 21 C 11.691 21 9 18.309 9 15 C 9 11.691 11.691 9 15 9 z M 15 11 A 4 4 0 0 0 11 15 A 4 4 0 0 0 15 19 A 4 4 0 0 0 19 15 A 4 4 0 0 0 15 11 z"

    ></path>

  </svg>

</a>



<!-- Github -->

<a href="https://github.com/skilldisk" target="_blank">

  <svg

    xmlns="http://www.w3.org/2000/svg"

    viewBox="0 0 30 30"

    class="w-8 h-8 fill-gray-900 hover:fill-primary dark:fill-gray-500 dark:hover:fill-primary"

  >

    <path

      d="M15,3C8.373,3,3,8.373,3,15c0,5.623,3.872,10.328,9.092,11.63C12.036,26.468,12,26.28,12,26.047v-2.051 c-0.487,0-1.303,0-1.508,0c-0.821,0-1.551-0.353-1.905-1.009c-0.393-0.729-0.461-1.844-1.435-2.526 c-0.289-0.227-0.069-0.486,0.264-0.451c0.615,0.174,1.125,0.596,1.605,1.222c0.478,0.627,0.703,0.769,1.596,0.769 c0.433,0,1.081-0.025,1.691-0.121c0.328-0.833,0.895-1.6,1.588-1.962c-3.996-0.411-5.903-2.399-5.903-5.098 c0-1.162,0.495-2.286,1.336-3.233C9.053,10.647,8.706,8.73,9.435,8c1.798,0,2.885,1.166,3.146,1.481C13.477,9.174,14.461,9,15.495,9 c1.036,0,2.024,0.174,2.922,0.483C18.675,9.17,19.763,8,21.565,8c0.732,0.731,0.381,2.656,0.102,3.594 c0.836,0.945,1.328,2.066,1.328,3.226c0,2.697-1.904,4.684-5.894,5.097C18.199,20.49,19,22.1,19,23.313v2.734 c0,0.104-0.023,0.179-0.035,0.268C23.641,24.676,27,20.236,27,15C27,8.373,21.627,3,15,3z"

    ></path>

  </svg>

</a>



<!-- Email -->

<a href="mailto:info@skilldisk.com" target="_blank">

  <svg

    xmlns="http://www.w3.org/2000/svg"

    class="h-8 w-8 fill-gray-700 hover:fill-primary dark:fill-gray-400 dark:hover:fill-primary"

    viewBox="0 0 20 20"

    fill="currentColor"

  >

    <path

      d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"

    />

    <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z" />

  </svg>

</a>



<!-- Telegram -->

<a href="https://t.me/+917829006066" target="_blank">

  <svg

    class="w-8 h-8 fill-[#0088cc] hover:fill-primary"

    xmlns="http://www.w3.org/2000/svg"

    viewBox="0 0 496 512"

  >

    <path

      d="M248,8C111.033,8,0,119.033,0,256S111.033,504,248,504,496,392.967,496,256,384.967,8,248,8ZM362.952,176.66c-3.732,39.215-19.881,134.378-28.1,178.3-3.476,18.584-10.322,24.816-16.948,25.425-14.4,1.326-25.338-9.517-39.287-18.661-21.827-14.308-34.158-23.215-55.346-37.177-24.485-16.135-8.612-25,5.342-39.5,3.652-3.793,67.107-61.51,68.335-66.746.153-.655.3-3.1-1.154-4.384s-3.59-.849-5.135-.5q-3.283.746-104.608,69.142-14.845,10.194-26.894,9.934c-8.855-.191-25.888-5.006-38.551-9.123-15.531-5.048-27.875-7.717-26.8-16.291q.84-6.7,18.45-13.7,108.446-47.248,144.628-62.3c68.872-28.647,83.183-33.623,92.511-33.789,2.052-.034,6.639.474,9.61,2.885a10.452,10.452,0,0,1,3.53,6.716A43.765,43.765,0,0,1,362.952,176.66Z"

    ></path>

  </svg>

</a>



<!-- Whatsapp -->

<a

  href="https://web.whatsapp.com/send?phone=+917829006066&amp;text=Hi, I would like to get more information about:"

  target="_blank"

  class="hidden lg:inline-block"

>

  <svg

    class="w-8 h-8 fill-[#075e54] hover:fill-primary"

    xmlns="http://www.w3.org/2000/svg"

    viewBox="0 0 448 512"

  >

    <path

      d="M380.9 97.1C339 55.1 283.2 32 223.9 32c-122.4 0-222 99.6-222 222 0 39.1 10.2 77.3 29.6 111L0 480l117.7-30.9c32.4 17.7 68.9 27 106.1 27h.1c122.3 0 224.1-99.6 224.1-222 0-59.3-25.2-115-67.1-157zm-157 341.6c-33.2 0-65.7-8.9-94-25.7l-6.7-4-69.8 18.3L72 359.2l-4.4-7c-18.5-29.4-28.2-63.3-28.2-98.2 0-101.7 82.8-184.5 184.6-184.5 49.3 0 95.6 19.2 130.4 54.1 34.8 34.9 56.2 81.2 56.1 130.5 0 101.8-84.9 184.6-186.6 184.6zm101.2-138.2c-5.5-2.8-32.8-16.2-37.9-18-5.1-1.9-8.8-2.8-12.5 2.8-3.7 5.6-14.3 18-17.6 21.8-3.2 3.7-6.5 4.2-12 1.4-32.6-16.3-54-29.1-75.5-66-5.7-9.8 5.7-9.1 16.3-30.3 1.8-3.7.9-6.9-.5-9.7-1.4-2.8-12.5-30.1-17.1-41.2-4.5-10.8-9.1-9.3-12.5-9.5-3.2-.2-6.9-.2-10.6-.2-3.7 0-9.7 1.4-14.8 6.9-5.1 5.6-19.4 19-19.4 46.3 0 27.3 19.9 53.7 22.6 57.4 2.8 3.7 39.1 59.7 94.8 83.8 35.2 15.2 49 16.5 66.6 13.9 10.7-1.6 32.8-13.4 37.4-26.4 4.6-13 4.6-24.1 3.2-26.4-1.3-2.5-5-3.9-10.5-6.6z"

    ></path>

  </svg>

</a>



<!-- Mobile Whatsapp -->

<a href="https://wa.me/917829006066" target="_blank" class="lg:hidden">

  <svg

    class="w-8 h-8 fill-[#075e54] hover:fill-primary"

    xmlns="http://www.w3.org/2000/svg"

    viewBox="0 0 448 512"

  >

    <path

      d="M380.9 97.1C339 55.1 283.2 32 223.9 32c-122.4 0-222 99.6-222 222 0 39.1 10.2 77.3 29.6 111L0 480l117.7-30.9c32.4 17.7 68.9 27 106.1 27h.1c122.3 0 224.1-99.6 224.1-222 0-59.3-25.2-115-67.1-157zm-157 341.6c-33.2 0-65.7-8.9-94-25.7l-6.7-4-69.8 18.3L72 359.2l-4.4-7c-18.5-29.4-28.2-63.3-28.2-98.2 0-101.7 82.8-184.5 184.6-184.5 49.3 0 95.6 19.2 130.4 54.1 34.8 34.9 56.2 81.2 56.1 130.5 0 101.8-84.9 184.6-186.6 184.6zm101.2-138.2c-5.5-2.8-32.8-16.2-37.9-18-5.1-1.9-8.8-2.8-12.5 2.8-3.7 5.6-14.3 18-17.6 21.8-3.2 3.7-6.5 4.2-12 1.4-32.6-16.3-54-29.1-75.5-66-5.7-9.8 5.7-9.1 16.3-30.3 1.8-3.7.9-6.9-.5-9.7-1.4-2.8-12.5-30.1-17.1-41.2-4.5-10.8-9.1-9.3-12.5-9.5-3.2-.2-6.9-.2-10.6-.2-3.7 0-9.7 1.4-14.8 6.9-5.1 5.6-19.4 19-19.4 46.3 0 27.3 19.9 53.7 22.6 57.4 2.8 3.7 39.1 59.7 94.8 83.8 35.2 15.2 49 16.5 66.6 13.9 10.7-1.6 32.8-13.4 37.4-26.4 4.6-13 4.6-24.1 3.2-26.4-1.3-2.5-5-3.9-10.5-6.6z"

    ></path>

  </svg>

</a>



      </div>

    </div>

  </div>



  <br />

  <div class="text-center grid">

    <p class="text-sm">&copy;Skill Disk 2023</p>

  </div>

  <br class="md:hidden" />

</footer>

<div

  class="z-[100] w-full bg-gray-100 dark:bg-gray-900 fixed bottom-0 p-2 flex md:hidden justify-evenly"

>

  <!-- Facebook -->

<a href="https://www.facebook.com/skilldisk" target="_blank">

  <svg

    class="w-8 h-8 fill-[#1877F2] hover:fill-primary"

    xmlns="http://www.w3.org/2000/svg"

    viewBox="0 0 24 24"

  >

    <path

      d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"

    />

  </svg>

</a>



<!-- Instagram -->

<a href="https://www.instagram.com/skill_disk/" target="_blank">

  <svg

    xmlns="http://www.w3.org/2000/svg"

    viewBox="0 0 30 30"

    class="w-8 h-8 fill-[#E1306C] hover:fill-primary"

  >

    <path

      d="M 9.9980469 3 C 6.1390469 3 3 6.1419531 3 10.001953 L 3 20.001953 C 3 23.860953 6.1419531 27 10.001953 27 L 20.001953 27 C 23.860953 27 27 23.858047 27 19.998047 L 27 9.9980469 C 27 6.1390469 23.858047 3 19.998047 3 L 9.9980469 3 z M 22 7 C 22.552 7 23 7.448 23 8 C 23 8.552 22.552 9 22 9 C 21.448 9 21 8.552 21 8 C 21 7.448 21.448 7 22 7 z M 15 9 C 18.309 9 21 11.691 21 15 C 21 18.309 18.309 21 15 21 C 11.691 21 9 18.309 9 15 C 9 11.691 11.691 9 15 9 z M 15 11 A 4 4 0 0 0 11 15 A 4 4 0 0 0 15 19 A 4 4 0 0 0 19 15 A 4 4 0 0 0 15 11 z"

    ></path>

  </svg>

</a>



<!-- Github -->

<a href="https://github.com/skilldisk" target="_blank">

  <svg

    xmlns="http://www.w3.org/2000/svg"

    viewBox="0 0 30 30"

    class="w-8 h-8 fill-gray-900 hover:fill-primary dark:fill-gray-500 dark:hover:fill-primary"

  >

    <path

      d="M15,3C8.373,3,3,8.373,3,15c0,5.623,3.872,10.328,9.092,11.63C12.036,26.468,12,26.28,12,26.047v-2.051 c-0.487,0-1.303,0-1.508,0c-0.821,0-1.551-0.353-1.905-1.009c-0.393-0.729-0.461-1.844-1.435-2.526 c-0.289-0.227-0.069-0.486,0.264-0.451c0.615,0.174,1.125,0.596,1.605,1.222c0.478,0.627,0.703,0.769,1.596,0.769 c0.433,0,1.081-0.025,1.691-0.121c0.328-0.833,0.895-1.6,1.588-1.962c-3.996-0.411-5.903-2.399-5.903-5.098 c0-1.162,0.495-2.286,1.336-3.233C9.053,10.647,8.706,8.73,9.435,8c1.798,0,2.885,1.166,3.146,1.481C13.477,9.174,14.461,9,15.495,9 c1.036,0,2.024,0.174,2.922,0.483C18.675,9.17,19.763,8,21.565,8c0.732,0.731,0.381,2.656,0.102,3.594 c0.836,0.945,1.328,2.066,1.328,3.226c0,2.697-1.904,4.684-5.894,5.097C18.199,20.49,19,22.1,19,23.313v2.734 c0,0.104-0.023,0.179-0.035,0.268C23.641,24.676,27,20.236,27,15C27,8.373,21.627,3,15,3z"

    ></path>

  </svg>

</a>



<!-- Email -->

<a href="mailto:info@skilldisk.com" target="_blank">

  <svg

    xmlns="http://www.w3.org/2000/svg"

    class="h-8 w-8 fill-gray-700 hover:fill-primary dark:fill-gray-400 dark:hover:fill-primary"

    viewBox="0 0 20 20"

    fill="currentColor"

  >

    <path

      d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"

    />

    <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z" />

  </svg>

</a>



<!-- Telegram -->

<a href="https://t.me/+917829006066" target="_blank">

  <svg

    class="w-8 h-8 fill-[#0088cc] hover:fill-primary"

    xmlns="http://www.w3.org/2000/svg"

    viewBox="0 0 496 512"

  >

    <path

      d="M248,8C111.033,8,0,119.033,0,256S111.033,504,248,504,496,392.967,496,256,384.967,8,248,8ZM362.952,176.66c-3.732,39.215-19.881,134.378-28.1,178.3-3.476,18.584-10.322,24.816-16.948,25.425-14.4,1.326-25.338-9.517-39.287-18.661-21.827-14.308-34.158-23.215-55.346-37.177-24.485-16.135-8.612-25,5.342-39.5,3.652-3.793,67.107-61.51,68.335-66.746.153-.655.3-3.1-1.154-4.384s-3.59-.849-5.135-.5q-3.283.746-104.608,69.142-14.845,10.194-26.894,9.934c-8.855-.191-25.888-5.006-38.551-9.123-15.531-5.048-27.875-7.717-26.8-16.291q.84-6.7,18.45-13.7,108.446-47.248,144.628-62.3c68.872-28.647,83.183-33.623,92.511-33.789,2.052-.034,6.639.474,9.61,2.885a10.452,10.452,0,0,1,3.53,6.716A43.765,43.765,0,0,1,362.952,176.66Z"

    ></path>

  </svg>

</a>



<!-- Whatsapp -->

<a

  href="https://web.whatsapp.com/send?phone=+917829006066&amp;text=Hi, I would like to get more information about:"

  target="_blank"

  class="hidden lg:inline-block"

>

  <svg

    class="w-8 h-8 fill-[#075e54] hover:fill-primary"

    xmlns="http://www.w3.org/2000/svg"

    viewBox="0 0 448 512"

  >

    <path

      d="M380.9 97.1C339 55.1 283.2 32 223.9 32c-122.4 0-222 99.6-222 222 0 39.1 10.2 77.3 29.6 111L0 480l117.7-30.9c32.4 17.7 68.9 27 106.1 27h.1c122.3 0 224.1-99.6 224.1-222 0-59.3-25.2-115-67.1-157zm-157 341.6c-33.2 0-65.7-8.9-94-25.7l-6.7-4-69.8 18.3L72 359.2l-4.4-7c-18.5-29.4-28.2-63.3-28.2-98.2 0-101.7 82.8-184.5 184.6-184.5 49.3 0 95.6 19.2 130.4 54.1 34.8 34.9 56.2 81.2 56.1 130.5 0 101.8-84.9 184.6-186.6 184.6zm101.2-138.2c-5.5-2.8-32.8-16.2-37.9-18-5.1-1.9-8.8-2.8-12.5 2.8-3.7 5.6-14.3 18-17.6 21.8-3.2 3.7-6.5 4.2-12 1.4-32.6-16.3-54-29.1-75.5-66-5.7-9.8 5.7-9.1 16.3-30.3 1.8-3.7.9-6.9-.5-9.7-1.4-2.8-12.5-30.1-17.1-41.2-4.5-10.8-9.1-9.3-12.5-9.5-3.2-.2-6.9-.2-10.6-.2-3.7 0-9.7 1.4-14.8 6.9-5.1 5.6-19.4 19-19.4 46.3 0 27.3 19.9 53.7 22.6 57.4 2.8 3.7 39.1 59.7 94.8 83.8 35.2 15.2 49 16.5 66.6 13.9 10.7-1.6 32.8-13.4 37.4-26.4 4.6-13 4.6-24.1 3.2-26.4-1.3-2.5-5-3.9-10.5-6.6z"

    ></path>

  </svg>

</a>



<!-- Mobile Whatsapp -->

<a href="https://wa.me/917829006066" target="_blank" class="lg:hidden">

  <svg

    class="w-8 h-8 fill-[#075e54] hover:fill-primary"

    xmlns="http://www.w3.org/2000/svg"

    viewBox="0 0 448 512"

  >

    <path

      d="M380.9 97.1C339 55.1 283.2 32 223.9 32c-122.4 0-222 99.6-222 222 0 39.1 10.2 77.3 29.6 111L0 480l117.7-30.9c32.4 17.7 68.9 27 106.1 27h.1c122.3 0 224.1-99.6 224.1-222 0-59.3-25.2-115-67.1-157zm-157 341.6c-33.2 0-65.7-8.9-94-25.7l-6.7-4-69.8 18.3L72 359.2l-4.4-7c-18.5-29.4-28.2-63.3-28.2-98.2 0-101.7 82.8-184.5 184.6-184.5 49.3 0 95.6 19.2 130.4 54.1 34.8 34.9 56.2 81.2 56.1 130.5 0 101.8-84.9 184.6-186.6 184.6zm101.2-138.2c-5.5-2.8-32.8-16.2-37.9-18-5.1-1.9-8.8-2.8-12.5 2.8-3.7 5.6-14.3 18-17.6 21.8-3.2 3.7-6.5 4.2-12 1.4-32.6-16.3-54-29.1-75.5-66-5.7-9.8 5.7-9.1 16.3-30.3 1.8-3.7.9-6.9-.5-9.7-1.4-2.8-12.5-30.1-17.1-41.2-4.5-10.8-9.1-9.3-12.5-9.5-3.2-.2-6.9-.2-10.6-.2-3.7 0-9.7 1.4-14.8 6.9-5.1 5.6-19.4 19-19.4 46.3 0 27.3 19.9 53.7 22.6 57.4 2.8 3.7 39.1 59.7 94.8 83.8 35.2 15.2 49 16.5 66.6 13.9 10.7-1.6 32.8-13.4 37.4-26.4 4.6-13 4.6-24.1 3.2-26.4-1.3-2.5-5-3.9-10.5-6.6z"

    ></path>

  </svg>

</a>



</div>





    <!-- Java Script -->

    



<script

  src="https://unpkg.com/htmx.org@1.6.1"

  integrity="sha384-tvG/2mnCFmGQzYC1Oh3qxQ7CkQ9kMzYjWZSNtrRZygHPDDqottzEJsqS4oUVodhW"

  crossorigin="anonymous"

></script>

<script defer src="https://unpkg.com/alpinejs@3.9.0/dist/cdn.min.js"></script>



<!-- Custom: Dark and Light theme setting js file -->

<script src="/static/js/dark_light_theme.js"></script>





    <!-- Extra JS -->

     



    <!-- whatsapp -->

    <!-- WhatsApp Floating Button -->

<div class="fixed bottom-8 right-8 hidden md:block">

  <a

    href="https://web.whatsapp.com/send?phone=+917829006066&amp;text=Hi, I would like to get more information about:"

    target="_blank"

    rel="noopener noreferrer"

    class="p-2 rounded-full"

  >

    <svg

      viewBox="0 0 31 31"

      class="inline w-10 h-10 stroke-transparent fill-secondary-light dark:stroke-transparent dark:fill-tertiary hover:fill-primary hover:stroke-primary dark:hover:fill-primary dark:hover:stroke-primary"

      fill="none"

      xmlns="http://www.w3.org/2000/svg"

    >

      <path

        d="M30.667,14.939c0,8.25-6.74,14.938-15.056,14.938c-2.639,0-5.118-0.675-7.276-1.857L0,30.667l2.717-8.017

    c-1.37-2.25-2.159-4.892-2.159-7.712C0.559,6.688,7.297,0,15.613,0C23.928,0.002,30.667,6.689,30.667,14.939z M15.61,2.382

    c-6.979,0-12.656,5.634-12.656,12.56c0,2.748,0.896,5.292,2.411,7.362l-1.58,4.663l4.862-1.545c2,1.312,4.393,2.076,6.963,2.076

    c6.979,0,12.658-5.633,12.658-12.559C28.27,8.016,22.59,2.382,15.61,2.382z M23.214,18.38c-0.094-0.151-0.34-0.243-0.708-0.427

    c-0.367-0.184-2.184-1.069-2.521-1.189c-0.34-0.123-0.586-0.185-0.832,0.182c-0.243,0.367-0.951,1.191-1.168,1.437

    c-0.215,0.245-0.43,0.276-0.799,0.095c-0.369-0.186-1.559-0.57-2.969-1.817c-1.097-0.972-1.838-2.169-2.052-2.536

    c-0.217-0.366-0.022-0.564,0.161-0.746c0.165-0.165,0.369-0.428,0.554-0.643c0.185-0.213,0.246-0.364,0.369-0.609

    c0.121-0.245,0.06-0.458-0.031-0.643c-0.092-0.184-0.829-1.984-1.138-2.717c-0.307-0.732-0.614-0.611-0.83-0.611

    c-0.215,0-0.461-0.03-0.707-0.03S9.897,8.215,9.56,8.582s-1.291,1.252-1.291,3.054c0,1.804,1.321,3.543,1.506,3.787

    c0.186,0.243,2.554,4.062,6.305,5.528c3.753,1.465,3.753,0.976,4.429,0.914c0.678-0.062,2.184-0.885,2.49-1.739

    C23.307,19.268,23.307,18.533,23.214,18.38z"

      />

    </svg>

  </a>

</div>



  </body>

</html>