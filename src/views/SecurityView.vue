<script setup>

import GreyBriefLogo from '../components/icons/GreyBriefLogo.vue'
import SecureBankingIcon from '../components/icons/security/SecureBankingIcon.vue'
import MultiFactor from '../components/icons/security/MultiFactor.vue'
import FraudMonitoring from '../components/icons/security/FraudMonitoring.vue'
import SecureMobile from '../components/icons/security/SecureMobile.vue'
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

      <p class="light-text mb-6">At YourBank, we prioritize the security and confidentiality of your financial information. Our state-of-the-art encryption technology and stringent data protection measures ensure your assets and transactions are safeguarded at all times</p>

      <div>
      
        <div>

          <div class="grid grid-cols-2 gap-4">
            <div class="security-card">

              <div class="flex items-center">
                <SecureBankingIcon />

                <p>Secure Online Banking Platform</p>
              </div>

              <p class="light-text">Our online banking platform is built with multiple layers of security to safeguard your information. We utilize industry-standard encryption protocols to ensure that your data remains confidential and protected during transmission.</p>

            </div>

            <div class="security-card">

              <div class="flex items-center">
                <MultiFactor />

                <p>Multi-Factor Authentication</p>
              </div>

              <p class="light-text">We provide a competitive salary package that recognizes the skills and expertise of
                our
                employees. YourBank believes in rewarding exceptional performance and offering opportunities for financial
                growth.</p>

            </div>

            <div class="security-card">

              <div class="flex items-center">
                <FraudMonitoring />

                <p>Fraud Monitoring</p>
              </div>

              <p class="light-text">We have sophisticated fraud detection systems in place to monitor your accounts for any suspicious activities. Our dedicated team works around the clock to detect and prevent unauthorized transactions, providing you with peace of mind.</p>

            </div>

            <div class="security-card">

              <div class="flex items-center">
                <SecureBankingIcon />

                <p>Secure Mobile Banking</p>
              </div>

              <p class="light-text">Our mobile banking app is designed with the same level of security as our online banking platform. You can confidently access your accounts, make transactions, and manage your finances on the go, knowing that your information is protected.</p>

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
          <p>What documents do I need to provide to apply for a loan?</p>

          <div style="background: #262626; height: 2px; margin-bottom: 10px; margin-top: 10px;"></div>

          <p class="light-text">The documents required for a loan application may vary depending on the type of loan you are applying for. Generally, you will need to provide identification documents (such as a passport or driver's license), proof of income (such as pay stubs or tax returns), and information about the collateral (if applicable). Our loan officers will guide you through the specific requirements during the application process.</p></div>

        <div class="faq-card">
          <p>How can I access my accounts online?</p>

          <div style="background: #262626; height: 2px; margin-bottom: 10px; margin-top: 10px;"></div>

          <p class="light-text">Accessing your accounts online is simple and secure. Visit our website and click on the "Login" button. Enter your username and password to access your accounts. If you haven't registered for online banking, click on the "Enroll Now" button and follow the registration process. If you need assistance, our customer support team is available to guide you.</p>
        </div>

        <div class="faq-card">
          <p>Are my transactions and personal information secure?</p>

          <div style="background: #262626; height: 2px; margin-bottom: 10px; margin-top: 10px;"></div>

          <p class="light-text">At YourBank, we prioritize the security of your transactions and personal information. We employ industry-leading encryption and multi-factor authentication to ensure that your data is protected. Additionally, we regularly update our security measures to stay ahead of emerging threats. You can bank with confidence knowing that we have robust security systems in place.</p>
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

.security-card {
  background-color: #1c1c1c;
  padding: 1.5rem;
  border-radius: 1.25rem 0rem 1.25rem 1.25rem;
}

.security-card>* {
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
