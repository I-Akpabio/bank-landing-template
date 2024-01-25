<script setup>

import GreyBriefLogo from '../components/icons/GreyBriefLogo.vue'
import BenefiIcon from '../components/icons/BenefiIcon.vue'
import NavBar from '../components/NavBar.vue'
</script>
<template>
  <div style="" class="container mx-auto px-8">
    <NavBar />
    <main>

      <div class="sub-container" style="padding: 2.5rem;">
        <div class="flex" style="position: relative;">
          <div class="left-hero">
            <h1 class="hero" style="font-size: 2.9rem">Your Security is our <span class="green-text">Top Priority </span>
            </h1>

            <p class="light-text">At YourBank, we understand the importance of keeping your financial information secure.
              We employ robust security measures and advanced technologies to protect your personal and financial data.
              Rest assured that when you bank with us, your security is our utmost priority.</p>
          </div>

          <div class="right-hero">
            <img style="" src="/images/security.png" alt="">
          </div>
        </div>
      </div>


    </main>



    <main style="margin-top: 15rem;">

      <h1 class="semi-big">How we <span class="green-text">Protect you</span></h1>

      <p class="light-text">Stay updated with the latest happenings and exciting developments at YourBank through our
        press
        releases.</p>

      <div>
        <div class="sub-container mt-4 mb-4" style="height: 300px; 
        border-radius: 3.125rem 3.125rem 1.25rem 1.25rem;
        background: linear-gradient(106deg, rgba(202, 255, 51, 0.05) -29.45%, rgba(202, 255, 51, 0.00) 27.86%), linear-gradient(267deg, #1C1C1C 40.67%, rgba(28, 28, 28, 0.00) 99.81%), url(<path-to-image>), lightgray 0% 0% / 62.46418356895447px 62.46418356895447px repeat;
        background-blend-mode: normal, normal, screen;">


        </div>
        <div>

          <div class="grid grid-cols-2 gap-4">
            <div class="press-card">

              <div class="flex items-center">
                <BenefiIcon />

                <p>Secure Online Banking Platform</p>
              </div>

              <p class="light-text">We provide a competitive salary package that recognizes the skills and expertise of
                our
                employees. YourBank believes in rewarding exceptional performance and offering opportunities for financial
                growth.</p>

            </div>

            <div class="press-card">

              <div class="flex items-center">
                <BenefiIcon />

                <p>Multi-Factor Authentication</p>
              </div>

              <p class="light-text">We provide a competitive salary package that recognizes the skills and expertise of
                our
                employees. YourBank believes in rewarding exceptional performance and offering opportunities for financial
                growth.</p>

            </div>

            <div class="press-card">

              <div class="flex items-center">
                <BenefiIcon />

                <p>Competitive Compensation</p>
              </div>

              <p class="light-text">We provide a competitive salary package that recognizes the skills and expertise of
                our
                employees. YourBank believes in rewarding exceptional performance and offering opportunities for financial
                growth.</p>

            </div>

            <div class="press-card">

              <div class="flex items-center">
                <BenefiIcon />

                <p>Competitive Compensation</p>
              </div>

              <p class="light-text">We provide a competitive salary package that recognizes the skills and expertise of
                our
                employees. YourBank believes in rewarding exceptional performance and offering opportunities for financial
                growth.</p>

            </div>
          </div>
        </div>
      </div>




    </main>



    <main>
      <h1 style="font-size: 38px;"><span class="green-text">Frequently</span> Asked Questions</h1>
      <p class="light-text">Still you have any questions? Contact our Team via support@yourbank.com</p>

      <div class="grid grid-cols-2 gap-4 top-margin">

        <div class="faq-card">
          <p>How do I open an account with YourBank?</p>

          <div style="background: #262626; height: 2px; margin-bottom: 10px; margin-top: 10px;"></div>

          <p class="light-text">Opening an account with YourBank is easy. Simply visit our website and click on the "Open
            an Account" button. Follow the prompts, provide the required information, and complete the application
            process. If you have any questions or need assistance, our customer support team is available to help.</p>
        </div>

        <div class="faq-card">
          <p>How do I open an account with YourBank?</p>

          <div style="background: #262626; height: 2px; margin-bottom: 10px; margin-top: 10px;"></div>

          <p class="light-text">Opening an account with YourBank is easy. Simply visit our website and click on the "Open
            an Account" button. Follow the prompts, provide the required information, and complete the application
            process. If you have any questions or need assistance, our customer support team is available to help.</p>
        </div>

        <div class="faq-card">
          <p>How do I open an account with YourBank?</p>

          <div style="background: #262626; height: 2px; margin-bottom: 10px; margin-top: 10px;"></div>

          <p class="light-text">Opening an account with YourBank is easy. Simply visit our website and click on the "Open
            an Account" button. Follow the prompts, provide the required information, and complete the application
            process. If you have any questions or need assistance, our customer support team is available to help.</p>
        </div>

        <div class="faq-card">
          <p>How do I open an account with YourBank?</p>

          <div style="background: #262626; height: 2px; margin-bottom: 10px; margin-top: 10px;"></div>

          <p class="light-text">Opening an account with YourBank is easy. Simply visit our website and click on the "Open
            an Account" button. Follow the prompts, provide the required information, and complete the application
            process. If you have any questions or need assistance, our customer support team is available to help.</p>
        </div>

      </div>

      <div class="flex justify-center mt-4"><button class="load-all-btn">
          Load All Faqs <svg width="18" height="19" viewBox="0 0 18 19" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M13.5 7.25L9 11.75L4.5 7.25" stroke="white" stroke-width="1.5" />
          </svg>
        </button>
      </div>
    </main>

  </div>
</template>

<style>
@media (min-width: 1024px) {}


.load-all-btn {
  border-radius: 6.25rem;
  border: 1px solid var(--Grey-15, #262626);
  background: var(--Grey-11, #1C1C1C);
  padding: 0.875rem 1.25rem;
}

.semi-big {
  font-size: 2.5rem;
}

.value-container {
  border-left: 1px solid var(--Green-60, #CAFF33);
  padding-left: 1.875rem;

}

.value-header {
  color: var(--Grey-30, #4C4C4D);
  font-size: 2.4rem;
  font-style: normal;
  font-weight: 500;
  line-height: 150%;
  /* 5.4375rem */
}

.value-text {
  color: var(--Grey-70, #B3B3B3);
  font-family: Lexend;
  font-size: 1rem;
  font-style: normal;
  font-weight: 300;
  line-height: 150%;
  /* 1.6875rem */
}

.left-hero {
  z-index: 3;
  background-color: #1a1a1a;
  padding: 3.75rem;
  border-radius: 1.25rem 0rem 3.75rem 1.25rem;
  width: 50%;
}

.right-hero {
  z-index: 1;
  position: absolute;
  right: 0;
  width: 70%;
  height: 80%;
}

.press-card {
  background-color: #1c1c1c;
  padding: 1.5rem;
  border-radius: 1.25rem 0rem 3.75rem 1.25rem;
}

.press-card>* {
  margin-bottom: 20px;
}

.press-header {
  line-height: 150%;
  font-size: 1.25rem;
  font-style: normal;
  font-weight: 400;
}

.press-info {
  color: var(--Grey-70, #B3B3B3);
  text-align: center;
  font-size: 1rem;
  font-style: normal;
  font-weight: 300;
  line-height: 150%;
  border-radius: 4.25rem;
  border: 1px solid var(--Grey-15, #262626);
  background: var(--Grey-10, #1A1A1A);
  padding: 0.375rem 0.875rem;
  margin-right: 10px;
}
</style>
