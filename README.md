portfolio project was built when i started learning javascript and it was built using html,css, javascript.
the project was about me .
so in the **header** there are 5 icons consists of HOME, EDUCATION, WORK, RECOMENDATION AND Projects.
in **sidnav** started with my basic details like name , role, age , residence .
the started with the progeamming languages known by me , skills and a button **Download CV**.
in the main block I detailed about the components
              1.Home - it consists of my name , role and about the role and a here me button.
              2.Education- it consists of my qualification like where i did my schooling and etc.
              3.work history- where and all i worked and for how many years , etc.
              4.Recommendations- about people who recommended me .
              5.projects - its about projects that i did ,and if you click on the icons, it will take you to my projects in the github
I used javascript for the icons in the header , if you click on the icon , perticular content about the component will be scrolled 
and we can view the content in that perticular content.






# portfolio
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portfolio</title>
    <link rel="stylesheet" href="portfolio.css" />
    <link rel="stylesheet" href="portfolio.js" />
  </head>
  <body>
    <header>
      <div class="menu-container">
        <ul class="header-ul" id="header-elems">
          <li class="icon-container active" id="1">
            <svg
              width="18"
              height="15"
              viewBox="0 0 18 15"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M15 13.9999C15 14.1989 14.921 14.3896 14.7803 14.5303C14.6397 14.6709 14.4489 14.7499 14.25 14.7499H3.75C3.55109 14.7499 3.36032 14.6709 3.21967 14.5303C3.07902 14.3896 3 14.1989 3 13.9999V7.24994H0.75L8.49525 0.20894C8.63333 0.0832983 8.81331 0.0136719 9 0.0136719C9.18669 0.0136719 9.36667 0.0832983 9.50475 0.20894L17.25 7.24994H15V13.9999Z"
                fill="#2B2B2B"
              />
            </svg>
          </li>
          <!--ctl+shift+c fo the image icon-->
          <li class="icon-container" id="2">
            <svg
              width="17"
              height="18"
              viewBox="0 0 17 18"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M11.7636 11.272L8.25 14.6259L4.73638 11.272C2.10301 11.381 0 13.4376 0 15.9759V16.3134C0 17.245 0.791853 18.0009 1.76786 18.0009H14.7321C15.7081 18.0009 16.5 17.245 16.5 16.3134V15.9759C16.5 13.4376 14.397 11.381 11.7636 11.272V11.272ZM0.500893 2.80635L0.736607 2.85909V4.91221C0.478795 5.05987 0.294643 5.31651 0.294643 5.62589C0.294643 5.9212 0.464063 6.16729 0.70346 6.31846L0.128906 8.5087C0.0662946 8.75128 0.20625 9.00089 0.408817 9.00089H1.94833C2.15089 9.00089 2.29085 8.75128 2.22824 8.5087L1.65368 6.31846C1.89308 6.16729 2.0625 5.9212 2.0625 5.62589C2.0625 5.31651 1.87835 5.05987 1.62054 4.91221V3.06299L4.05134 3.62198C3.7346 4.22667 3.53571 4.90167 3.53571 5.62589C3.53571 8.11143 5.64609 10.1259 8.25 10.1259C10.8539 10.1259 12.9643 8.11143 12.9643 5.62589C12.9643 4.90167 12.7691 4.22667 12.4487 3.62198L15.9954 2.80635C16.6657 2.65166 16.6657 1.85362 15.9954 1.69893L8.98292 0.0817384C8.50413 -0.0272461 7.99955 -0.0272461 7.52076 0.0817384L0.500893 1.69541C-0.165737 1.8501 -0.165737 2.65166 0.500893 2.80635V2.80635Z"
                fill="black"
              />
            </svg>
          </li>
          <li class="icon-container" id="3">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M5.75 9.75V12H10.25V9.75H15.5V15C15.5 15.1989 15.421 15.3897 15.2803 15.5303C15.1397 15.671 14.9489 15.75 14.75 15.75H1.25C1.05109 15.75 0.860322 15.671 0.71967 15.5303C0.579018 15.3897 0.5 15.1989 0.5 15V9.75H5.75ZM7.25 8.25H8.75V10.5H7.25V8.25ZM4.25 3.75V1.5C4.25 1.30109 4.32902 1.11032 4.46967 0.96967C4.61032 0.829018 4.80109 0.75 5 0.75H11C11.1989 0.75 11.3897 0.829018 11.5303 0.96967C11.671 1.11032 11.75 1.30109 11.75 1.5V3.75H14.75C14.9489 3.75 15.1397 3.82902 15.2803 3.96967C15.421 4.11032 15.5 4.30109 15.5 4.5V8.25H10.25V6.75H5.75V8.25H0.5V4.5C0.5 4.30109 0.579018 4.11032 0.71967 3.96967C0.860322 3.82902 1.05109 3.75 1.25 3.75H4.25ZM5.75 2.25V3.75H10.25V2.25H5.75Z"
                fill="#2B2B2B"
              />
            </svg>
          </li>
          <li class="icon-container" id="4">
            <svg
              width="16"
              height="15"
              viewBox="0 0 16 15"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M3.84125 12.25L0.5 14.875V1C0.5 0.801088 0.579018 0.610322 0.71967 0.46967C0.860322 0.329018 1.05109 0.25 1.25 0.25H14.75C14.9489 0.25 15.1397 0.329018 15.2803 0.46967C15.421 0.610322 15.5 0.801088 15.5 1V11.5C15.5 11.6989 15.421 11.8897 15.2803 12.0303C15.1397 12.171 14.9489 12.25 14.75 12.25H3.84125Z"
                fill="#2B2B2B"
              />
            </svg>
          </li>
          <li class="icon-container" id="5">
            <svg
              width="14"
              height="16"
              viewBox="0 0 14 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M13.75 0.5C2.5 0.5 1 11 0.25 15.5H1.7485C2.248 13.0003 3.49825 11.6255 5.5 11.375C8.5 11 10.75 8.375 11.5 6.125L10.375 5.375L11.125 4.625C11.875 3.875 12.628 2.75 13.75 0.5Z"
                fill="#2B2B2B"
              />
            </svg>
          </li>
        </ul>
      </div>
    </header>
    <div class="content-container">
      <div class="side-nav">
        <div class="display-picture"></div>
        <div class="name-container">S.Neeraj</div>
        <div class="title-container">Full Stack Developer</div>
        <div class="social-links">
          <ul class="social-ul">
            <li>
              <span class="social-icons"
                ><svg
                  width="7"
                  height="12"
                  viewBox="0 0 7 12"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M4.16659 6.87484H5.62492L6.20825 4.5415H4.16659V3.37484C4.16659 2.774 4.16659 2.20817 5.33325 2.20817H6.20825V0.248171C6.01809 0.223087 5.3 0.166504 4.54167 0.166504C2.95792 0.166504 1.83325 1.13309 1.83325 2.90817V4.5415H0.083252V6.87484H1.83325V11.8332H4.16659V6.87484Z"
                    fill="#1B1B1B"
                  />
                </svg>
              </span>
            </li>
            <li>
              <span class="social-icons"
                ><svg
                  width="13"
                  height="13"
                  viewBox="0 0 13 13"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M6.49984 0.666504C8.08475 0.666504 8.2825 0.672337 8.90434 0.701504C9.52559 0.730671 9.9485 0.828087 10.3207 0.972754C10.7057 1.12092 11.03 1.32159 11.3543 1.64534C11.651 1.93694 11.8805 2.28968 12.0269 2.679C12.171 3.05059 12.269 3.47409 12.2982 4.09534C12.3256 4.71717 12.3332 4.91492 12.3332 6.49984C12.3332 8.08475 12.3273 8.2825 12.2982 8.90434C12.269 9.52559 12.171 9.9485 12.0269 10.3207C11.8809 10.7102 11.6513 11.063 11.3543 11.3543C11.0626 11.6509 10.7099 11.8804 10.3207 12.0269C9.94909 12.171 9.52559 12.269 8.90434 12.2982C8.2825 12.3256 8.08475 12.3332 6.49984 12.3332C4.91492 12.3332 4.71717 12.3273 4.09534 12.2982C3.47409 12.269 3.05117 12.171 2.679 12.0269C2.28953 11.8808 1.93673 11.6512 1.64534 11.3543C1.34866 11.0628 1.11913 10.71 0.972754 10.3207C0.828087 9.94909 0.730671 9.52559 0.701504 8.90434C0.674087 8.2825 0.666504 8.08475 0.666504 6.49984C0.666504 4.91492 0.672337 4.71717 0.701504 4.09534C0.730671 3.4735 0.828087 3.05117 0.972754 2.679C1.11873 2.28944 1.34831 1.93661 1.64534 1.64534C1.93681 1.34856 2.28959 1.11901 2.679 0.972754C3.05117 0.828087 3.4735 0.730671 4.09534 0.701504C4.71717 0.674087 4.91492 0.666504 6.49984 0.666504ZM6.49984 3.58317C5.72629 3.58317 4.98442 3.89046 4.43744 4.43744C3.89046 4.98442 3.58317 5.72629 3.58317 6.49984C3.58317 7.27339 3.89046 8.01525 4.43744 8.56223C4.98442 9.10921 5.72629 9.4165 6.49984 9.4165C7.27339 9.4165 8.01525 9.10921 8.56223 8.56223C9.10921 8.01525 9.4165 7.27339 9.4165 6.49984C9.4165 5.72629 9.10921 4.98442 8.56223 4.43744C8.01525 3.89046 7.27339 3.58317 6.49984 3.58317ZM10.2915 3.43734C10.2915 3.24395 10.2147 3.05848 10.0779 2.92174C9.94119 2.78499 9.75572 2.70817 9.56234 2.70817C9.36895 2.70817 9.18348 2.78499 9.04674 2.92174C8.90999 3.05848 8.83317 3.24395 8.83317 3.43734C8.83317 3.63072 8.90999 3.81619 9.04674 3.95294C9.18348 4.08968 9.36895 4.1665 9.56234 4.1665C9.75572 4.1665 9.94119 4.08968 10.0779 3.95294C10.2147 3.81619 10.2915 3.63072 10.2915 3.43734ZM6.49984 4.74984C6.96397 4.74984 7.40909 4.93421 7.73727 5.2624C8.06546 5.59059 8.24984 6.03571 8.24984 6.49984C8.24984 6.96397 8.06546 7.40909 7.73727 7.73727C7.40909 8.06546 6.96397 8.24984 6.49984 8.24984C6.03571 8.24984 5.59059 8.06546 5.2624 7.73727C4.93421 7.40909 4.74984 6.96397 4.74984 6.49984C4.74984 6.03571 4.93421 5.59059 5.2624 5.2624C5.59059 4.93421 6.03571 4.74984 6.49984 4.74984Z"
                    fill="#2B2B2B"
                  />
                </svg>
              </span>
            </li>
            <li>
              <span class="social-icons"
                ><svg
                  width="12"
                  height="11"
                  viewBox="0 0 12 11"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M2.54818 1.41676C2.54802 1.72618 2.42496 2.02287 2.20606 2.24155C1.98715 2.46023 1.69035 2.583 1.38093 2.58285C1.07151 2.58269 0.774823 2.45963 0.55614 2.24072C0.337457 2.02182 0.214689 1.72501 0.214844 1.4156C0.214999 1.10618 0.338063 0.809491 0.556965 0.590808C0.775867 0.372125 1.07267 0.249357 1.38209 0.249512C1.69151 0.249667 1.9882 0.372731 2.20688 0.591633C2.42556 0.810535 2.54833 1.10734 2.54818 1.41676V1.41676ZM2.58318 3.44676H0.249844V10.7501H2.58318V3.44676ZM6.26984 3.44676H3.94818V10.7501H6.24651V6.9176C6.24651 4.7826 9.02901 4.58426 9.02901 6.9176V10.7501H11.3332V6.12426C11.3332 2.5251 7.21484 2.65926 6.24651 4.42676L6.26984 3.44676V3.44676Z"
                    fill="#2B2B2B"
                  />
                </svg>
              </span>
            </li>
            <li>
              <span class="social-icons">
                <svg
                  width="13"
                  height="11"
                  viewBox="0 0 13 11"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M12.0666 2.29066C12.3332 3.33016 12.3332 5.50016 12.3332 5.50016C12.3332 5.50016 12.3332 7.67016 12.0666 8.70966C11.9184 9.28425 11.485 9.73633 10.9361 9.88916C9.93917 10.1668 6.49984 10.1668 6.49984 10.1668C6.49984 10.1668 3.06225 10.1668 2.06359 9.88916C1.51234 9.734 1.0795 9.2825 0.933087 8.70966C0.666504 7.67016 0.666504 5.50016 0.666504 5.50016C0.666504 5.50016 0.666504 3.33016 0.933087 2.29066C1.08125 1.71608 1.51467 1.264 2.06359 1.11116C3.06225 0.833496 6.49984 0.833496 6.49984 0.833496C6.49984 0.833496 9.93917 0.833496 10.9361 1.11116C11.4873 1.26633 11.9202 1.71783 12.0666 2.29066ZM5.33317 7.54183L8.83317 5.50016L5.33317 3.4585V7.54183Z"
                    fill="#2B2B2B"
                  />
                </svg>
              </span>
            </li>
            <li>
              <span class="social-icons"
                ><svg
                  width="13"
                  height="13"
                  viewBox="0 0 13 13"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M11.1601 6.25017C11.1123 5.33195 10.7929 4.44861 10.2425 3.71209C10.0748 3.8927 9.89554 4.06223 9.70584 4.21959C9.12304 4.70366 8.47179 5.09878 7.77325 5.39209C7.87067 5.59625 7.95992 5.794 8.03867 5.98067V5.98242C8.06089 6.03458 8.08228 6.08709 8.10284 6.13992C8.986 6.04075 9.917 6.07692 10.8194 6.19884C10.9396 6.21517 11.0528 6.23267 11.1601 6.25017ZM5.6855 1.90434C6.25398 2.70535 6.77821 3.53688 7.25584 4.39517C7.96925 4.114 8.559 3.75934 9.03384 3.36442C9.19866 3.22858 9.35381 3.08142 9.49817 2.924C8.65874 2.21801 7.59668 1.83161 6.49984 1.83317C6.22686 1.83298 5.95438 1.8566 5.6855 1.90375V1.90434ZM1.98075 5.33142C2.37814 5.32139 2.77505 5.29746 3.17075 5.25967C4.12721 5.17412 5.0755 5.0138 6.00692 4.78017C5.52014 3.93446 4.99458 3.11167 4.43192 2.31442C3.83092 2.61215 3.30099 3.03566 2.87806 3.55621C2.45514 4.07677 2.14912 4.68219 1.98075 5.33142ZM2.87325 9.43692C3.09959 9.10617 3.39709 8.734 3.792 8.32917C4.64017 7.46 5.64117 6.78334 6.79967 6.41L6.83584 6.3995C6.73959 6.18717 6.64917 5.99759 6.55817 5.81909C5.48717 6.13117 4.359 6.326 3.23492 6.42692C2.68659 6.4765 2.19484 6.49809 1.83317 6.50159C1.83214 7.5706 2.19968 8.60729 2.87384 9.43692H2.87325ZM8.25275 10.8253C8.0278 9.69082 7.70938 8.57694 7.30075 7.495C6.13292 7.91909 5.2025 8.53917 4.48325 9.27884C4.19299 9.57189 3.9354 9.8956 3.715 10.2443C4.51931 10.8444 5.49632 11.1679 6.49984 11.1665C7.10062 11.1674 7.69588 11.0519 8.25275 10.8264V10.8253ZM9.34534 10.1982C10.2561 9.49803 10.8765 8.4865 11.0878 7.35734C10.8894 7.30775 10.638 7.25817 10.3615 7.21967C9.74675 7.13115 9.12296 7.12467 8.5065 7.20042C8.85362 8.17974 9.13388 9.18148 9.34534 10.1988V10.1982ZM6.49984 12.3332C3.27809 12.3332 0.666504 9.72159 0.666504 6.49984C0.666504 3.27809 3.27809 0.666504 6.49984 0.666504C9.72159 0.666504 12.3332 3.27809 12.3332 6.49984C12.3332 9.72159 9.72159 12.3332 6.49984 12.3332Z"
                    fill="#2B2B2B"
                  />
                </svg>
              </span>
            </li>
            <li>
              <span class="social-icons"
                ><svg
                  width="13"
                  height="11"
                  viewBox="0 0 13 11"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M12.4277 1.79953C11.9823 1.99652 11.5101 2.12589 11.0265 2.18337C11.5362 1.87854 11.9177 1.39879 12.0998 0.833535C11.6215 1.1182 11.0971 1.3177 10.5505 1.42562C10.1834 1.03279 9.69672 0.772263 9.16624 0.684542C8.63575 0.596822 8.09115 0.686821 7.61709 0.940549C7.14303 1.19428 6.76607 1.59752 6.54483 2.08758C6.32359 2.57764 6.27045 3.12707 6.39368 3.65045C5.42366 3.60183 4.47471 3.34976 3.60843 2.91059C2.74216 2.47142 1.97792 1.85498 1.36535 1.10128C1.14852 1.47371 1.03457 1.89708 1.03518 2.32803C1.03518 3.17387 1.46568 3.92112 2.12018 4.35862C1.73285 4.34642 1.35405 4.24182 1.01535 4.05354V4.08387C1.01546 4.64719 1.2104 5.19314 1.56709 5.62915C1.92379 6.06516 2.4203 6.3644 2.97243 6.47612C2.61287 6.57356 2.23586 6.58792 1.86993 6.51812C2.0256 7.003 2.32902 7.42707 2.73769 7.73093C3.14637 8.0348 3.63984 8.20325 4.14901 8.2127C3.64296 8.61014 3.06353 8.90394 2.44386 9.0773C1.82419 9.25066 1.17642 9.30018 0.537598 9.22303C1.65275 9.9402 2.9509 10.3209 4.27676 10.3197C8.76435 10.3197 11.2184 6.60212 11.2184 3.37804C11.2184 3.27304 11.2155 3.16687 11.2108 3.06303C11.6885 2.7178 12.1008 2.29013 12.4283 1.80012L12.4277 1.79953Z"
                    fill="#2B2B2B"
                  />
                </svg>
              </span>
            </li>
          </ul>
        </div>
        <hr class="breakline" />
        <div class="personal-details-container">
          <div class="personal-details">
            <p class="property">Age :</p>
            <span class="value">24</span>
          </div>
          <div class="personal-details">
            <p class="property">Residence :</p>
            <span class="value">TamilNadu</span>
          </div>
          <div class="personal-details">
            <p class="property">Address :</p>
            <span class="value">Hosur</span>
          </div>
        </div>
        <hr class="breakline" />
        <div class="languages">
          <h4 style="font-weight: 500">Languages</h4>
          <div class="personal-details">
            <p class="property-lang">English :</p>
            <span class="property-val">80%</span>
          </div>
          <div class="progress">
            <span class="current-progress"></span>
          </div>
          <div class="personal-details">
            <p class="property-lang">Kannada :</p>
            <span class="property-val">85%</span>
          </div>
          <div class="progress">
            <span class="current-progress" style="width: 11%"></span>
          </div>
          <div class="personal-details">
            <p class="property-lang">Tamli :</p>
            <span class="property-val">75%</span>
          </div>
          <div class="progress">
            <span class="current-progress" style="width: 9%"></span>
          </div>
        </div>
        <hr class="breakline" />
        <div class="skills">
          <h4 style="font-weight: 500">Skills</h4>
          <div class="personal-details">
            <p class="property-lang">Html :</p>
            <span class="property-val">80%</span>
          </div>
          <div class="progress">
            <span class="current-progress"></span>
          </div>
          <div class="personal-details">
            <p class="property-lang">Css :</p>
            <span class="property-val">85%</span>
          </div>
          <div class="progress">
            <span class="current-progress" style="width: 11%"></span>
          </div>
          <div class="personal-details">
            <p class="property-lang">Javascript :</p>
            <span class="property-val">75%</span>
          </div>
          <div class="progress">
            <span class="current-progress" style="width: 9%"></span>
          </div>
        </div>
        <hr class="breakline" />
        <div class="extra-skills">
          <h4 style="font-weight: 500">Extra-Skills</h4>
          <div>
            <svg
              class="skill-icon"
              width="11"
              height="11"
              viewBox="0 0 11 11"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <rect x="1" y="1" width="9" height="9" stroke="#FFB400" />
            </svg>
            <span class="eskills">Bootstrap,Materialize</span>
          </div>
          <div>
            <svg
              class="skill-icon"
              width="11"
              height="11"
              viewBox="0 0 11 11"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <rect x="1" y="1" width="9" height="9" stroke="#FFB400" />
            </svg>
            <span class="eskills">Git knowledge</span>
          </div>
          <div>
            <svg
              class="skill-icon"
              width="11"
              height="11"
              viewBox="0 0 11 11"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <rect x="1" y="1" width="9" height="9" stroke="#FFB400" />
            </svg>
            <span class="eskills">AWS</span>
          </div>
          <div>
            <svg
              class="skill-icon"
              width="11"
              height="11"
              viewBox="0 0 11 11"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <rect x="1" y="1" width="9" height="9" stroke="#FFB400" />
            </svg>
            <span class="eskills">DSA</span>
          </div>
        </div>
        <hr class="breakline" />
        <button class="download">
          Download CV
          <svg
            class="cv"
            width="13"
            height="13"
            viewBox="0 0 13 13"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M1.83317 11.4523H11.1665V6.78564H12.3332V12.119C12.3332 12.2958 12.2717 12.4654 12.1623 12.5904C12.0529 12.7154 11.9045 12.7856 11.7498 12.7856H1.24984C1.09513 12.7856 0.946754 12.7154 0.837358 12.5904C0.727962 12.4654 0.666504 12.2958 0.666504 12.119V6.78564H1.83317V11.4523ZM7.6665 4.78564H10.5832L6.49984 9.45231L2.4165 4.78564H5.33317V0.785645H7.6665V4.78564Z"
              fill="#2B2B2B"
            />
          </svg>
        </button>
      </div>
      <div class="content-main">
        <div class="intro">
          <div class="intro-headings">
            <span class="mydescription">
              I'm S.Neeraj
              <span class="colored-desc">Full Stack</span> Developer
            </span>
            <p class="detailed-desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam
              deserunt, officia culpa doloribus perferendis totam mollitia, sit
              fugiat similique vitae ad repudiandae optio at explicabo illo
              dolor? Unde, ipsum possimus?
            </p>
            <button class="hireme">
              Hire me
              <svg
                class="arrow"
                width="12"
                height="12"
                viewBox="0 0 12 12"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M8.78117 5.33312L5.20517 1.75712L6.14784 0.814453L11.3332 5.99979L6.14784 11.1851L5.20517 10.2425L8.78117 6.66645H0.666504V5.33312H8.78117Z"
                  fill="#2B2B2B"
                />
              </svg>
            </button>
          </div>
          <div class="big-dp"><img src="face.jpg" alt="" /></div>
        </div>
        <!-- mobile details -->
        <div class="mobile-mydetails">
          <div class="mobile-personal-details"></div>
          <div class="mobile-display-picture"></div>
          <div class="mobile-name-container">S.Neeraj</div>
          <div class="mobile-title-container">Full Stack Developer</div>
          <div class="social-links">
            <ul class="social-ul">
              <li>
                <span class="social-icons"
                  ><svg
                    width="7"
                    height="12"
                    viewBox="0 0 7 12"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M4.16659 6.87484H5.62492L6.20825 4.5415H4.16659V3.37484C4.16659 2.774 4.16659 2.20817 5.33325 2.20817H6.20825V0.248171C6.01809 0.223087 5.3 0.166504 4.54167 0.166504C2.95792 0.166504 1.83325 1.13309 1.83325 2.90817V4.5415H0.083252V6.87484H1.83325V11.8332H4.16659V6.87484Z"
                      fill="#1B1B1B"
                    />
                  </svg>
                </span>
              </li>
              <li>
                <span class="social-icons"
                  ><svg
                    width="13"
                    height="13"
                    viewBox="0 0 13 13"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M6.49984 0.666504C8.08475 0.666504 8.2825 0.672337 8.90434 0.701504C9.52559 0.730671 9.9485 0.828087 10.3207 0.972754C10.7057 1.12092 11.03 1.32159 11.3543 1.64534C11.651 1.93694 11.8805 2.28968 12.0269 2.679C12.171 3.05059 12.269 3.47409 12.2982 4.09534C12.3256 4.71717 12.3332 4.91492 12.3332 6.49984C12.3332 8.08475 12.3273 8.2825 12.2982 8.90434C12.269 9.52559 12.171 9.9485 12.0269 10.3207C11.8809 10.7102 11.6513 11.063 11.3543 11.3543C11.0626 11.6509 10.7099 11.8804 10.3207 12.0269C9.94909 12.171 9.52559 12.269 8.90434 12.2982C8.2825 12.3256 8.08475 12.3332 6.49984 12.3332C4.91492 12.3332 4.71717 12.3273 4.09534 12.2982C3.47409 12.269 3.05117 12.171 2.679 12.0269C2.28953 11.8808 1.93673 11.6512 1.64534 11.3543C1.34866 11.0628 1.11913 10.71 0.972754 10.3207C0.828087 9.94909 0.730671 9.52559 0.701504 8.90434C0.674087 8.2825 0.666504 8.08475 0.666504 6.49984C0.666504 4.91492 0.672337 4.71717 0.701504 4.09534C0.730671 3.4735 0.828087 3.05117 0.972754 2.679C1.11873 2.28944 1.34831 1.93661 1.64534 1.64534C1.93681 1.34856 2.28959 1.11901 2.679 0.972754C3.05117 0.828087 3.4735 0.730671 4.09534 0.701504C4.71717 0.674087 4.91492 0.666504 6.49984 0.666504ZM6.49984 3.58317C5.72629 3.58317 4.98442 3.89046 4.43744 4.43744C3.89046 4.98442 3.58317 5.72629 3.58317 6.49984C3.58317 7.27339 3.89046 8.01525 4.43744 8.56223C4.98442 9.10921 5.72629 9.4165 6.49984 9.4165C7.27339 9.4165 8.01525 9.10921 8.56223 8.56223C9.10921 8.01525 9.4165 7.27339 9.4165 6.49984C9.4165 5.72629 9.10921 4.98442 8.56223 4.43744C8.01525 3.89046 7.27339 3.58317 6.49984 3.58317ZM10.2915 3.43734C10.2915 3.24395 10.2147 3.05848 10.0779 2.92174C9.94119 2.78499 9.75572 2.70817 9.56234 2.70817C9.36895 2.70817 9.18348 2.78499 9.04674 2.92174C8.90999 3.05848 8.83317 3.24395 8.83317 3.43734C8.83317 3.63072 8.90999 3.81619 9.04674 3.95294C9.18348 4.08968 9.36895 4.1665 9.56234 4.1665C9.75572 4.1665 9.94119 4.08968 10.0779 3.95294C10.2147 3.81619 10.2915 3.63072 10.2915 3.43734ZM6.49984 4.74984C6.96397 4.74984 7.40909 4.93421 7.73727 5.2624C8.06546 5.59059 8.24984 6.03571 8.24984 6.49984C8.24984 6.96397 8.06546 7.40909 7.73727 7.73727C7.40909 8.06546 6.96397 8.24984 6.49984 8.24984C6.03571 8.24984 5.59059 8.06546 5.2624 7.73727C4.93421 7.40909 4.74984 6.96397 4.74984 6.49984C4.74984 6.03571 4.93421 5.59059 5.2624 5.2624C5.59059 4.93421 6.03571 4.74984 6.49984 4.74984Z"
                      fill="#2B2B2B"
                    />
                  </svg>
                </span>
              </li>
              <li>
                <span class="social-icons"
                  ><svg
                    width="12"
                    height="11"
                    viewBox="0 0 12 11"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M2.54818 1.41676C2.54802 1.72618 2.42496 2.02287 2.20606 2.24155C1.98715 2.46023 1.69035 2.583 1.38093 2.58285C1.07151 2.58269 0.774823 2.45963 0.55614 2.24072C0.337457 2.02182 0.214689 1.72501 0.214844 1.4156C0.214999 1.10618 0.338063 0.809491 0.556965 0.590808C0.775867 0.372125 1.07267 0.249357 1.38209 0.249512C1.69151 0.249667 1.9882 0.372731 2.20688 0.591633C2.42556 0.810535 2.54833 1.10734 2.54818 1.41676V1.41676ZM2.58318 3.44676H0.249844V10.7501H2.58318V3.44676ZM6.26984 3.44676H3.94818V10.7501H6.24651V6.9176C6.24651 4.7826 9.02901 4.58426 9.02901 6.9176V10.7501H11.3332V6.12426C11.3332 2.5251 7.21484 2.65926 6.24651 4.42676L6.26984 3.44676V3.44676Z"
                      fill="#2B2B2B"
                    />
                  </svg>
                </span>
              </li>
              <li>
                <span class="social-icons">
                  <svg
                    width="13"
                    height="11"
                    viewBox="0 0 13 11"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M12.0666 2.29066C12.3332 3.33016 12.3332 5.50016 12.3332 5.50016C12.3332 5.50016 12.3332 7.67016 12.0666 8.70966C11.9184 9.28425 11.485 9.73633 10.9361 9.88916C9.93917 10.1668 6.49984 10.1668 6.49984 10.1668C6.49984 10.1668 3.06225 10.1668 2.06359 9.88916C1.51234 9.734 1.0795 9.2825 0.933087 8.70966C0.666504 7.67016 0.666504 5.50016 0.666504 5.50016C0.666504 5.50016 0.666504 3.33016 0.933087 2.29066C1.08125 1.71608 1.51467 1.264 2.06359 1.11116C3.06225 0.833496 6.49984 0.833496 6.49984 0.833496C6.49984 0.833496 9.93917 0.833496 10.9361 1.11116C11.4873 1.26633 11.9202 1.71783 12.0666 2.29066ZM5.33317 7.54183L8.83317 5.50016L5.33317 3.4585V7.54183Z"
                      fill="#2B2B2B"
                    />
                  </svg>
                </span>
              </li>
              <li>
                <span class="social-icons"
                  ><svg
                    width="13"
                    height="13"
                    viewBox="0 0 13 13"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M11.1601 6.25017C11.1123 5.33195 10.7929 4.44861 10.2425 3.71209C10.0748 3.8927 9.89554 4.06223 9.70584 4.21959C9.12304 4.70366 8.47179 5.09878 7.77325 5.39209C7.87067 5.59625 7.95992 5.794 8.03867 5.98067V5.98242C8.06089 6.03458 8.08228 6.08709 8.10284 6.13992C8.986 6.04075 9.917 6.07692 10.8194 6.19884C10.9396 6.21517 11.0528 6.23267 11.1601 6.25017ZM5.6855 1.90434C6.25398 2.70535 6.77821 3.53688 7.25584 4.39517C7.96925 4.114 8.559 3.75934 9.03384 3.36442C9.19866 3.22858 9.35381 3.08142 9.49817 2.924C8.65874 2.21801 7.59668 1.83161 6.49984 1.83317C6.22686 1.83298 5.95438 1.8566 5.6855 1.90375V1.90434ZM1.98075 5.33142C2.37814 5.32139 2.77505 5.29746 3.17075 5.25967C4.12721 5.17412 5.0755 5.0138 6.00692 4.78017C5.52014 3.93446 4.99458 3.11167 4.43192 2.31442C3.83092 2.61215 3.30099 3.03566 2.87806 3.55621C2.45514 4.07677 2.14912 4.68219 1.98075 5.33142ZM2.87325 9.43692C3.09959 9.10617 3.39709 8.734 3.792 8.32917C4.64017 7.46 5.64117 6.78334 6.79967 6.41L6.83584 6.3995C6.73959 6.18717 6.64917 5.99759 6.55817 5.81909C5.48717 6.13117 4.359 6.326 3.23492 6.42692C2.68659 6.4765 2.19484 6.49809 1.83317 6.50159C1.83214 7.5706 2.19968 8.60729 2.87384 9.43692H2.87325ZM8.25275 10.8253C8.0278 9.69082 7.70938 8.57694 7.30075 7.495C6.13292 7.91909 5.2025 8.53917 4.48325 9.27884C4.19299 9.57189 3.9354 9.8956 3.715 10.2443C4.51931 10.8444 5.49632 11.1679 6.49984 11.1665C7.10062 11.1674 7.69588 11.0519 8.25275 10.8264V10.8253ZM9.34534 10.1982C10.2561 9.49803 10.8765 8.4865 11.0878 7.35734C10.8894 7.30775 10.638 7.25817 10.3615 7.21967C9.74675 7.13115 9.12296 7.12467 8.5065 7.20042C8.85362 8.17974 9.13388 9.18148 9.34534 10.1988V10.1982ZM6.49984 12.3332C3.27809 12.3332 0.666504 9.72159 0.666504 6.49984C0.666504 3.27809 3.27809 0.666504 6.49984 0.666504C9.72159 0.666504 12.3332 3.27809 12.3332 6.49984C12.3332 9.72159 9.72159 12.3332 6.49984 12.3332Z"
                      fill="#2B2B2B"
                    />
                  </svg>
                </span>
              </li>
              <li>
                <span class="social-icons"
                  ><svg
                    width="13"
                    height="11"
                    viewBox="0 0 13 11"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M12.4277 1.79953C11.9823 1.99652 11.5101 2.12589 11.0265 2.18337C11.5362 1.87854 11.9177 1.39879 12.0998 0.833535C11.6215 1.1182 11.0971 1.3177 10.5505 1.42562C10.1834 1.03279 9.69672 0.772263 9.16624 0.684542C8.63575 0.596822 8.09115 0.686821 7.61709 0.940549C7.14303 1.19428 6.76607 1.59752 6.54483 2.08758C6.32359 2.57764 6.27045 3.12707 6.39368 3.65045C5.42366 3.60183 4.47471 3.34976 3.60843 2.91059C2.74216 2.47142 1.97792 1.85498 1.36535 1.10128C1.14852 1.47371 1.03457 1.89708 1.03518 2.32803C1.03518 3.17387 1.46568 3.92112 2.12018 4.35862C1.73285 4.34642 1.35405 4.24182 1.01535 4.05354V4.08387C1.01546 4.64719 1.2104 5.19314 1.56709 5.62915C1.92379 6.06516 2.4203 6.3644 2.97243 6.47612C2.61287 6.57356 2.23586 6.58792 1.86993 6.51812C2.0256 7.003 2.32902 7.42707 2.73769 7.73093C3.14637 8.0348 3.63984 8.20325 4.14901 8.2127C3.64296 8.61014 3.06353 8.90394 2.44386 9.0773C1.82419 9.25066 1.17642 9.30018 0.537598 9.22303C1.65275 9.9402 2.9509 10.3209 4.27676 10.3197C8.76435 10.3197 11.2184 6.60212 11.2184 3.37804C11.2184 3.27304 11.2155 3.16687 11.2108 3.06303C11.6885 2.7178 12.1008 2.29013 12.4283 1.80012L12.4277 1.79953Z"
                      fill="#2B2B2B"
                    />
                  </svg>
                </span>
              </li>
            </ul>
          </div>
          <div class="mobile-contact-details">
            <div class="personal-details-container">
              <div class="personal-details">
                <p class="property">Age :</p>
                <span class="value">24</span>
              </div>
              <div class="personal-details">
                <p class="property">Residence :</p>
                <span class="value">TamilNadu</span>
              </div>
              <div class="personal-details">
                <p class="property">Address :</p>
                <span class="value">Hosur</span>
              </div>
            </div>
          </div>
          <div class="languages">
            <h4 style="font-weight: 500">Languages</h4>
            <div class="personal-details">
              <p class="property-lang">English :</p>
              <span class="property-val">80%</span>
            </div>
            <div class="progress">
              <span class="current-progress"></span>
            </div>
            <div class="personal-details">
              <p class="property-lang">Kannada :</p>
              <span class="property-val">85%</span>
            </div>
            <div class="progress">
              <span class="current-progress" style="width: 11%"></span>
            </div>
            <div class="personal-details">
              <p class="property-lang">Tamli :</p>
              <span class="property-val">75%</span>
            </div>
            <div class="progress">
              <span class="current-progress" style="width: 9%"></span>
            </div>
          </div>
          <!-- SKILLS -->
          <div class="skills">
            <h4 style="font-weight: 500">Skills</h4>
            <div class="personal-details">
              <p class="property-lang">Html :</p>
              <span class="property-val">80%</span>
            </div>
            <div class="progress">
              <span class="current-progress"></span>
            </div>
            <div class="personal-details">
              <p class="property-lang">Css :</p>
              <span class="property-val">85%</span>
            </div>
            <div class="progress">
              <span class="current-progress" style="width: 11%"></span>
            </div>
            <div class="personal-details">
              <p class="property-lang">Javascript :</p>
              <span class="property-val">75%</span>
            </div>
            <div class="progress">
              <span class="current-progress" style="width: 9%"></span>
            </div>
          </div>
          <!-- EXTRA SKILLS -->
          <div class="extra-skills">
            <h4 style="font-weight: 500">Extra-Skills</h4>
            <div>
              <svg
                class="skill-icon"
                width="11"
                height="11"
                viewBox="0 0 11 11"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <rect x="1" y="1" width="9" height="9" stroke="#FFB400" />
              </svg>
              <span class="eskills">Bootstrap,Materialize</span>
            </div>
            <div>
              <svg
                class="skill-icon"
                width="11"
                height="11"
                viewBox="0 0 11 11"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <rect x="1" y="1" width="9" height="9" stroke="#FFB400" />
              </svg>
              <span class="eskills">Git knowledge</span>
            </div>
            <div>
              <svg
                class="skill-icon"
                width="11"
                height="11"
                viewBox="0 0 11 11"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <rect x="1" y="1" width="9" height="9" stroke="#FFB400" />
              </svg>
              <span class="eskills">AWS</span>
            </div>
            <div>
              <svg
                class="skill-icon"
                width="11"
                height="11"
                viewBox="0 0 11 11"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <rect x="1" y="1" width="9" height="9" stroke="#FFB400" />
              </svg>
              <span class="eskills">DSA</span>
            </div>
          </div>
          <button class="download">
            Download CV
            <svg
              class="cv"
              width="13"
              height="13"
              viewBox="0 0 13 13"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M1.83317 11.4523H11.1665V6.78564H12.3332V12.119C12.3332 12.2958 12.2717 12.4654 12.1623 12.5904C12.0529 12.7154 11.9045 12.7856 11.7498 12.7856H1.24984C1.09513 12.7856 0.946754 12.7154 0.837358 12.5904C0.727962 12.4654 0.666504 12.2958 0.666504 12.119V6.78564H1.83317V11.4523ZM7.6665 4.78564H10.5832L6.49984 9.45231L2.4165 4.78564H5.33317V0.785645H7.6665V4.78564Z"
                fill="#2B2B2B"
              />
            </svg>
          </button>
        </div>
        <h2 class="heading">Education</h2>
        <p class="sub-heading">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ullam fugiat
          necessitatibus ea, voluptate deserunt sit, laudantium fugit, qui
          minima possimus sunt incidunt.
        </p>
        <div class="edu-div">
          <div class="edu-section">
            <div class="edu-name">
              <p class="edu-text-1">University Name</p>
              <p class="edu-text-2">
                Duration <span class="duration">Jan2020-June2024</span>
              </p>
            </div>
            <div class="edu-desc">
              <p class="edu-text-1">Certificate of web training</p>
              <p class="edu-text-3">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Tenetur tempore in corrupti beatae, voluptatem explicabo numquam
                totam cupiditate voluptatum reprehenderit modi exercitationem
                alias earum est iure qui. Excepturi, et voluptate.
              </p>
            </div>
          </div>
          <hr class="breakline" />
          <div class="edu-section">
            <div class="edu-name">
              <p class="edu-text-1">University Name</p>
              <p class="edu-text-2">
                Duration <span class="duration">Jan2020-June2024</span>
              </p>
            </div>
            <div class="edu-desc">
              <p class="edu-text-1">Certificate of web training</p>
              <p class="edu-text-3">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Tenetur tempore in corrupti beatae, voluptatem explicabo numquam
                totam cupiditate voluptatum reprehenderit modi exercitationem
                alias earum est iure qui. Excepturi, et voluptate.
              </p>
            </div>
          </div>
          <hr class="breakline" />

          <div class="edu-section">
            <div class="edu-name">
              <p class="edu-text-1">University Name</p>
              <p class="edu-text-2">
                Duration <span class="duration">Jan2020-June2024</span>
              </p>
            </div>
            <div class="edu-desc">
              <p class="edu-text-1">Certificate of web training</p>
              <p class="edu-text-3">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Tenetur tempore in corrupti beatae, voluptatem explicabo numquam
                totam cupiditate voluptatum reprehenderit modi exercitationem
                alias earum est iure qui. Excepturi, et voluptate.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <h2 class="work">Work History</h2>
    <p class="subwork-heading">
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ullam fugiat
      necessitatibus ea, voluptate deserunt sit, laudantium fugit, qui minima
      possimus sunt incidunt.
    </p>
    <div class="work-div">
      <div class="edu-section">
        <div class="edu-name">
          <p class="edu-text-1">University Name</p>
          <p class="edu-text-2">
            Duration <span class="duration">Jan2020-June2024</span>
          </p>
        </div>
        <div class="edu-desc">
          <p class="edu-text-1">Certificate of web training</p>
          <p class="edu-text-3">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tenetur
            tempore in corrupti beatae, voluptatem explicabo numquam totam
            cupiditate voluptatum reprehenderit modi exercitationem alias earum
            est iure qui. Excepturi, et voluptate.
          </p>
        </div>
      </div>
      <hr class="breakline" />

      <div class="edu-section">
        <div class="edu-name">
          <p class="edu-text-1">University Name</p>
          <p class="edu-text-2">
            Duration <span class="duration">Jan2020-June2024</span>
          </p>
        </div>
        <div class="edu-desc">
          <p class="edu-text-1">Certificate of web training</p>
          <p class="edu-text-3">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tenetur
            tempore in corrupti beatae, voluptatem explicabo numquam totam
            cupiditate voluptatum reprehenderit modi exercitationem alias earum
            est iure qui. Excepturi, et voluptate.
          </p>
        </div>
      </div>
      <hr class="breakline" />

      <div class="edu-section">
        <div class="edu-name">
          <p class="edu-text-1">University Name</p>
          <p class="edu-text-2">
            Duration <span class="duration">Jan2020-June2024</span>
          </p>
        </div>
        <div class="edu-desc">
          <p class="edu-text-1">Certificate of web training</p>
          <p class="edu-text-3">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tenetur
            tempore in corrupti beatae, voluptatem explicabo numquam totam
            cupiditate voluptatum reprehenderit modi exercitationem alias earum
            est iure qui. Excepturi, et voluptate.
          </p>
        </div>
      </div>
    </div>
    <div class="section">
      <h2 class="headings">Recommendations</h2>
      <p class="subwork-heading">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ullam fugiat
        necessitatibus ea, voluptate deserunt sit, laudantium fugit, qui minima
        possimus sunt incidunt.
      </p>
      <div class="cards-container">
        <div class="Cards">
          <div class="Card">
            <div class="star-rating">
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
            </div>
            <p class="comment">Great work!!</p>
            <p class="detailed-comment">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Reiciendis, unde veritatis aspernatur eveniet ea hic quae quidem,
              saepe voluptates impedit.
            </p>
            <div class="testimonial">
              <div class="test-dp"></div>
              <div class="test-detail">
                <p class="test-name">James Gouse</p>
                <p class="test-title">Graphic Designer</p>
              </div>
            </div>
          </div>
          <div class="Card">
            <div class="star-rating">
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
            </div>
            <!--wait-->
            <p class="comment">Great work!!</p>
            <p class="detailed-comment">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Reiciendis, unde veritatis aspernatur eveniet ea hic quae quidem,
              saepe voluptates impedit.
            </p>
            <div class="testimonial">
              <div class="test-dp"></div>
              <div class="test-detail">
                <p class="test-name">James Gouse</p>
                <p class="test-title">Graphic Designer</p>
              </div>
            </div>
          </div>
          <div class="Card">
            <div class="star-rating">
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"
                  fill="#FFB400"
                />
              </svg>
            </div>
            <p class="comment">Great work!!</p>
            <p class="detailed-comment">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Reiciendis, unde veritatis aspernatur eveniet ea hic quae quidem,
              saepe voluptates impedit.
            </p>
            <div class="testimonial">
              <div class="test-dp"></div>
              <div class="test-detail">
                <p class="test-name">James Gouse</p>
                <p class="test-title">Graphic Designer</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <h2 class="work">Projects</h2>
    <p class="subwork-heading">
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ullam fugiat
      necessitatibus ea, voluptate deserunt sit, laudantium fugit, qui minima
      possimus sunt incidunt.
    </p>
    <div class="cards-container">
      <div class="Cards" id="project-container">
        <a href="https://github.com"
          ><div class="project-card" id="card1"></div
        ></a>
        <a href="https://github.com"
          ><div class="project-card" id="card2"></div
        ></a>
        <a href="https://github.com"
          ><div class="project-card" id="card3"></div
        ></a>
      </div>
    </div>
    <footer class="my-footer">
      <div class="footer-text">2023. All Rights Reserved</div>
    </footer>
    <script src="portfolio.js"></script>
  </body>
</html>

<<<<....SCROLL DOWN FOR CSS...>>>>
body {
  margin: 0;
  padding: 0;
  background: rgb(232, 229, 229);
}
.menu-container {
  background-color: white;
  height: 80px;
  box-shadow: 0px 0px 2px 0px grey;
  width: 113%;
  z-index: 1;
}
.mobile-mydetails {
  display: none;
}
ul {
  margin: 0;
}
.header-ul > li {
  padding: 15px;
  display: inline-block;
  margin-top: 10px;
  margin-left: 5px;
}
.social-ul > li {
  display: inline-block;
}
.content-container {
  display: flex;
  margin-top: 2px;
}
.side-nav {
  width: 15%;
  height: 150vh;
  background-color: white;
  display: flex;
  flex-direction: column;
  padding: 50px 46px 0 40px;
}
.content-main {
  margin-left: 20px;
  width: 85%;
}

.icon-container {
  height: 18px;
  width: 18px;
  display: block;
  border-radius: 50%;
  background-color: #f8f4ea;
  padding: 8px;
  cursor: pointer;
}
.active {
  background-color: #ffb400;
}
.display-picture {
  width: 100px;
  height: 120px;
  background-color: white;
  border-radius: 50%;
  margin: 0 auto;
  background-image: url("face.jpg");
  background-size: cover;
  background-repeat: no-repeat;
}
.name-container {
  text-align: center;
  margin-top: 31px;
  margin-left: auto;
  margin-right: auto;
  font-weight: 500;
  font-size: 18px;
  line-height: 123.6%;
}

.title-container {
  margin-top: 15px;
  color: #767676;
  font-style: normal;
  font-weight: 400;
  font-size: 15px;
  line-height: 24px;
  text-transform: capitalize;
  margin-left: auto;
  margin-right: auto;
}
.social-links {
  margin-top: 20px;
  margin-left: auto;
  margin-right: auto;
  padding: 1px;
}
.social-icons {
  margin-top: 20px;
  margin-left: auto;
  width: 24px;
  height: 24px;
  border-radius: 50%;
  background-color: #ffb400;
  padding: 8px;
  border-radius: 50%;
}
.social-ul {
  margin-left: -12px;
  margin-right: 1px;
  padding: 10px;
}
.breakline {
  background-color: black;
  width: 100%;
  margin-top: 20px;
  opacity: 0.5;
}
.property {
  margin: 0;
  background-color: #ffb400;
  padding-right: 5px;
}
.personal-details-conatiner {
  margin-top: 20px;
}
.personal-details {
  display: flex;
  justify-content: space-between;
  margin-top: 10px;
}
.progress {
  background-color: #f6f6f9;
  width: 100%;
  height: 4px;
  border-radius: 10px;
  padding-top: 2px;
  border: 1px solid #ffb400;
  padding-left: 1px;
}
.current-progress {
  position: absolute;
  display: inline-block;
  background-color: #ffb400;
  width: 10%;
  height: 2px;
}
.property-lang {
  margin: 0;
  opacity: 0.5;
  margin-bottom: 5px;
}
.property-val {
  opacity: 0.5;
}
.skill-icon {
  padding-right: 10px;
}
.eskills {
  opacity: 0.5;
  margin-left: 10px;
}
.download {
  background-color: #ffb400;
  text-transform: uppercase;
  border: none;
  width: 100%;
  height: 40px;
  margin-top: 10px;
  cursor: pointer;
}
.cv {
  margin-left: 30px;
}
.intro {
  display: flex;
  justify-content: space-between;
  background-color: #fff;
  width: 970px;
  height: 467px;
  margin: auto;
}
.intro-headings {
  width: 50%;
  margin-left: 57px;
  margin-left: 93px;
}

.mydescription {
  font-family: "Inter";
  font-style: normal;
  font-weight: 700;
  font-size: 48px;
  line-height: 123.6%;
  color: #2b2b2b;
}
.colored-desc {
  color: #ffb400;
}
.detailed-desc {
  opacity: 0.5;
  width: 424px;
  height: 88px;
}
.hireme {
  background-color: #ffb400;
  border-radius: 5px;
  text-transform: uppercase;
  border: none;
  padding: 20px;
}
.arrow {
  margin-left: 20px;
}
.big-dp {
  margin-left: auto;
  margin-right: auto;
}
.heading {
  text-align: center;
  margin-top: 50px;
  font-size: 32px;
  font-weight: 700;
  font-style: normal;
  line-height: 123.6%;
  text-transform: capitalize;
  color: black;
}
.sub-heading {
  font-style: normal;
  font-weight: 400;
  font-size: 15px;
  line-height: 24px;
  text-align: center;
  text-transform: capitalize;
  font-feature-settings: "calt" off, "kern" off;
  color: #2b2b2b;
  width: 40%;
  height: 68px;
  margin: auto;
  opacity: 0.5;
}
.edu-div {
  width: 970px;

  background-color: #fff;
  margin-right: auto;
  margin-left: 85px;
  margin-top: 50px;
  padding: 49px 29px 38px 40px;
}
.edu-section {
  display: flex;
  justify-content: space-between;
}
.edu-name {
  width: 40%;
}
.edu-desc {
  width: 60%;
}
.edu-text-1 {
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 123.6%;
  text-transform: capitalize;
  color: #2b2b2b;
}
.edu-text-2 {
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 123.6%;
  text-transform: capitalize;
  color: #2b2b2b;
}
.edu-text-3 {
  font-style: normal;
  font-weight: 400;
  font-size: 15px;
  line-height: 24px;
  opacity: 0.5;
  text-transform: capitalize;
  font-feature-settings: "calt" off, "kern" off;
  color: #2b2b2b;
  /*width: 40%;
    height: 68px;
    margin: auto;  */
}
.duration {
  background-color: #ffb400;
  width: 111px;
  height: 18px;
  color: #fff;
  padding: 0 5px 0 5px;
  font-size: 14px;
  margin-left: 10px;
}
.work {
  margin-left: 350px;
  text-align: center;
  text-align: center;
  margin-top: 50px;
  font-size: 32px;
  font-weight: 700;
  font-style: normal;
  line-height: 123.6%;
  text-transform: capitalize;
  color: black;
}
.subwork-heading {
  font-style: normal;
  font-weight: 400;
  font-size: 15px;
  line-height: 24px;
  text-align: center;
  text-transform: capitalize;
  font-feature-settings: "calt" off, "kern" off;
  color: #2b2b2b;
  width: 40%;
  height: 68px;
  margin: auto;
  opacity: 0.5;
  margin-left: 625px;
}
.work-div {
  width: 970px;

  background-color: #fff;
  margin-right: auto;
  margin-left: 410px;
  margin-top: 50px;
  padding: 49px 29px 38px 40px;
}
.headings {
  margin-left: 400px;
  text-align: center;
  margin-top: 50px;
  font-size: 32px;
  font-weight: 700;
  font-style: normal;
  line-height: 123.6%;
  text-transform: capitalize;
  color: black;
}
.cards-container {
  text-align: center;
  margin-left: auto;
  margin-right: 30px;
  width: 1039px;
  /*background-color: aqua;*/
  margin-top: 50px;
}
.Cards {
  display: flex;
  justify-content: space-between;
}
.Card {
  width: 230px;
  height: 280px;
  background-color: #fff;
  padding: 40px;
  margin-left: 10px;
  justify-content: baseline;
}
.star-rating {
  margin-left: -150px;
}
.comment {
  margin-left: -170px;
}
.detailed-comment {
  margin-left: -13px;
  justify-content: center;
  width: 262px;
  height: 89px;
  font-style: normal;
  font-size: 15px;
  font-weight: 400;
  line-height: 24px;
  text-transform: capitalize;
  font-feature-settings: "calt" off, "kern" off;
  color: #767676;
}
.testimonial {
  display: flex;
  margin-top: 40px;
}
.test-dp {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  background-color: #767676;
  /*width: 20%;*/
  background-image: url(face.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
.test-detail {
  margin-top: 1px;
  /*width: 80%;*/
}
.test-name {
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 123.6%;
  text-transform: capitalize;
  color: #100c0c;
  margin-left: 10px;
}
.test-title {
  margin: 0;
  padding: 0;
  margin-left: 20px;
  margin-top: -20px;
  font-style: normal;
  font-weight: 400;
  font-size: 15px;
  line-height: 24px;
  text-transform: capitalize;
  font-feature-settings: "calt" off, "kern" off;
  color: #767676;
}
.project-card {
  width: 230px;
  height: 280px;
  background-color: #fff;
  padding: 40px;
  margin-left: 10px;
  justify-content: baseline;
  cursor: pointer;
  /* to redirect */
}
#card1 {
  background-image: url("card1.svg");
}
#card2 {
  background-image: url("card2.svg");
}
#card3 {
  background-image: url("card3.svg");
}
.my-footer {
  width: 100%;
  height: 100%;
  background-color: #fff;
  margin-top: 50px;
  display: flex;
}
.footer-text {
  margin: 0 auto;
  width: fit-content;
  display: flex;
  /* text-align: center; */
  padding: 30px;
  /* margin-top: -30px; */
  align-items: center;
}

@media only screen and (max-width: 600px) {
  .mobile-mydetails {
    display: inline-block;
    width: 109%;
    justify-content: space-between;
    background-color: #fff;
    /* height: 100px; */
    margin-top: 20px;
    margin-left: auto;
    margin-right: auto;
    /* padding: 20px; */
    padding: 10px;
    flex-wrap: wrap;
  }
  .mobile-display-picture {
    width: 50px;
    height: 50px;
    background-color: white;
    border-radius: 50%;
    background-image: url("face.jpg");
    background-size: contain;
    background-repeat: no-repeat;
    margin: 0 auto;
    padding: 10px;
    margin-left: 0%;
  }
  .mobile-personal-details {
    margin: o auto;
    font-size: 12px;
    /* width: 50%; */
  }
  .mobile-contact-details {
    width: 50%;
  }
  .languages {
    /* width: 50%; */
  }
  .skills {
    /* width: 50%; */
  }

  .mobile-name-container {
    margin: 0 auto;
    width: fit-content;
    font-size: 12px;
    margin-left: 2%;
  }
  .mobile-title-container {
    margin: 0 auto;
    width: fit-content;
    font-size: 12px;
    margin-left: 2%;
  }

  .social-links {
    margin-top: 5px;
  }
  .social-icons {
    margin-left: 5px;
  }
  .side-nav {
    display: none;
  }
  .content-main {
    margin-left: 0;
    width: 100%;
  }
  .intro {
    width: 113%;
    height: 350px;
  }
  .intro-headings {
    margin-left: 20px;
    margin-top: 50px;
  }
  .mydescription {
    font-size: 36px;
    line-height: 120%;
  }
  .detailed-desc {
    width: 300px;
    height: 110px;
  }
  .big-dp > img {
    height: 200px;
    width: 175px;
    margin-top: 140px;
  }
  .hireme {
    padding: 10px;
  }
  .sub-heading {
    width: 106%;
    height: 70px;
  }
  .edu-div {
    width: 100%;
    margin-left: 5px;
    padding: 25px;
    margin-top: 15px;
  }
  .edu-name {
    width: 52%;
  }
  .edu-text-2 {
    font-size: 14px;
  }
  .duration {
    font-size: 12px;
  }
  .edu-desc {
    width: 70%;
  }
  .edu-text-3 {
    font-size: 14px;
  }
  .work {
    width: 100%;
    margin-left: -30px;
    padding: 25px;
    margin-top: 0px;
    margin-bottom: -10px;
    font-size: 50px;
  }
  .subwork-heading {
    width: 100%;
    height: 70px;
    margin-left: 10px;
  }
  .work-div {
    width: 105%;
    margin-left: 10px;
    padding: 10px;
    margin-top: 10px;
  }
  .heading {
    margin-top: 15px;
    margin-bottom: 10px;
  }
  .headings {
    font-size: 40px;
    margin-left: 50px;
    margin-top: 10px;
    margin-bottom: 10px;
  }

  .cards-container {
    width: 80%;
    margin-top: 10px;
  }
  .Cards {
    overflow: scroll;
    scroll-snap-align: center;
    scroll-behavior: smooth;
  }
  .Card {
    padding: 80px;
  }
  .project-card {
    padding: 80px;
  }
}


<<<<...SCROLL FOR JAVASCRIPT....>>>>

var header = document.getElementById("header-elems");
var menuItems = header.getElementsByClassName("icon-container");
const projectContainerEl = document.getElementById("project-container");
const starratingEl = document.getElementById("star-rating");
for (var i = 0; i < menuItems.length; i++) {
  menuItems[i].addEventListener("click", function () {
    var currentItem = document.getElementsByClassName(" active");
    currentItem[0].className = currentItem[0].className.replace("active", "");
    this.className = this.className + " active";
    //console.log(this.id);
    var level = this.id;
    if (level == 1) {
      window.scroll({
        top: 0,
        left: 0,
        behavior: "smooth",
      });
    } else if (level == "2") {
      window.scroll({
        top: level * 300,
        left: 0,
        behavior: "smooth",
      });
    } else if (level == "3") {
      window.scroll({
        top: level * 470,
        left: 0,
        behavior: "smooth",
      });
    } else if (level == "4") {
      window.scroll({
        top: level * 530,
        left: 0,
        behavior: "smooth",
      });
    } else {
      window.scroll({
        top: 3000,
        left: 0,
        behavior: "smooth",
      });
    }
  });
}
// or you can use switch case
// switch (level) {
//     case "1":
//         window.scroll({
//             top: level * 530,
//             left: 0,
//             behavior: "smooth",
//         });
//         break;
//     case "2":
//         window.scroll({
//             top: level * 530,
//             left: 0,
//             behavior: "smooth",
//         });
//         break;
//     case "3":
//         window.scroll({
//             top: level * 530,
//             left: 0,
//             behavior: "smooth",
//         });
//         break;
//     case "4":
//         window.scroll({
//             top: level * 530,
//             left: 0,
//             behavior: "smooth",
//         });
//         break;
//     case "5":
//         window.scroll({
//             top: level * 530,
//             left: 0,
//             behavior: "smooth",
//         });
//         break;
//     }

//var str = "tomorrow is  extra class";
//str = str.replace("tomorrow","today");
//console.log(str);

// for (let i = 1; i <= 3; i++) {
//   projectContainerEl.innerHTML += '<a href="https://github.com"><div class="project-card" id="card${i}"></div></a>`;
// }
// for (let i = 1; i <= 5; i++){
//     starratingEl.innerHTML += '<svg width="18" height="18"viewBox="0 0 18 18"fill="none"xmlns="http://www.w3.org/2000/svg"><path d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"fill="#FFB400"/></svg><div class="project-card" id="star${i}"></div>';
// }
