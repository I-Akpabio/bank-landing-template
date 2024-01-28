<script setup>
import FooterView from "../components/FooterView.vue";
import GreyBriefLogo from "../components/icons/GreyBriefLogo.vue";
import BenefiIcon from "../components/icons/BenefiIcon.vue";
import NavBar from "../components/NavBar.vue";
</script>
<template>
  <div class="container mx-auto px-8">
    <NavBar />

    <main>
      <div class="sub-container" style="padding: 2.5rem">
        <div class="flex" style="position: relative">
          <div style="width: 50%" class="left-hero">
            <p>Welcome to YourBank</p>
            <h1 class="hero">
              Welcome to <span class="green-text">YourBank </span>Careers!
            </h1>

            <p class="light-text">
              Join our team and embark on a rewarding journey in the banking
              industry. At YourBank, we are committed to fostering a culture of
              excellence and providing opportunities for professional growth.
              With a focus on innovation, customer service, and integrity, we
              strive to make a positive impact in the lives of our customers and
              communities. Join us today and be a part of our mission to shape
              the future of banking.
            </p>
          </div>

          <div class="right-hero">
            <img style="" src="/images/career-hero.png" alt="" />
          </div>
        </div>
      </div>
    </main>

    <main style="margin-top: 16rem">
      <h1 class="green-text semi-big">Our Values</h1>

      <p class="light-text">
        We envision being a leading force in the industry, driven by innovation,
        integrity, and inclusivity, creating a brighter financial future for
        individuals and businesses while maintaining a strong commitment to
        customer satisfaction and community development
      </p>

      <div class="grid grid-cols-2 gap-7 top-margin">
        <div class="value-container">
          <div class="value-header">Integrity</div>

          <p class="value-text">
            We conduct ourselves with utmost honesty, transparency, and ethical
            behavior. We believe in doing what is right for our customers,
            colleagues, and stakeholders, even when faced with difficult
            choices.
          </p>
        </div>

        <div class="value-container">
          <div class="value-header">Customer Centricity</div>

          <p class="value-text">
            We conduct ourselves with utmost honesty, transparency, and ethical
            behavior. We believe in doing what is right for our customers,
            colleagues, and stakeholders, even when faced with difficult
            choices.
          </p>
        </div>

        <div class="value-container">
          <div class="value-header">Collaboration</div>

          <p class="value-text">
            We conduct ourselves with utmost honesty, transparency, and ethical
            behavior. We believe in doing what is right for our customers,
            colleagues, and stakeholders, even when faced with difficult
            choices.
          </p>
        </div>

        <div class="value-container">
          <div class="value-header">Innovation</div>

          <p class="value-text">
            We conduct ourselves with utmost honesty, transparency, and ethical
            behavior. We believe in doing what is right for our customers,
            colleagues, and stakeholders, even when faced with difficult
            choices.
          </p>
        </div>
      </div>
    </main>

    <main>
      <h1 class="semi-big">Our <span class="green-text">Benefits</span></h1>

      <p class="light-text">
        Stay updated with the latest happenings and exciting developments at
        YourBank through our press releases.
      </p>

      <div class="grid grid-cols-2 top-margin gap-4">
        <div class="press-card">
          <div class="flex items-center">
            <BenefiIcon />

            <p>Competitive Compensation</p>
          </div>

          <p class="light-text">
            We provide a competitive salary package that recognizes the skills
            and expertise of our employees. YourBank believes in rewarding
            exceptional performance and offering opportunities for financial
            growth.
          </p>
        </div>

        <div class="press-card">
          <div class="flex items-center">
            <BenefiIcon />

            <p>Competitive Compensation</p>
          </div>

          <p class="light-text">
            We provide a competitive salary package that recognizes the skills
            and expertise of our employees. YourBank believes in rewarding
            exceptional performance and offering opportunities for financial
            growth.
          </p>
        </div>

        <div class="press-card">
          <div class="flex items-center">
            <BenefiIcon />

            <p>Competitive Compensation</p>
          </div>

          <p class="light-text">
            We provide a competitive salary package that recognizes the skills
            and expertise of our employees. YourBank believes in rewarding
            exceptional performance and offering opportunities for financial
            growth.
          </p>
        </div>

        <div class="press-card">
          <div class="flex items-center">
            <BenefiIcon />

            <p>Competitive Compensation</p>
          </div>

          <p class="light-text">
            We provide a competitive salary package that recognizes the skills
            and expertise of our employees. YourBank believes in rewarding
            exceptional performance and offering opportunities for financial
            growth.
          </p>
        </div>
      </div>
    </main>

    <main>
      <h1 class="green-text semi-big">Job Opening</h1>

      <p class="light-text">
        Stay updated with the latest happenings and exciting developments at
        YourBank through our press releases.
      </p>

      <div class="grid grid-cols-2 top-margin gap-4">
        <div class="press-card">
          <div class="img-container-1"></div>

          <p class="press-header">Relationship Manager</p>

          <div>
            <span class="press-info">Location: India</span>
            <span class="press-info">Date: 06/11/2024</span>
          </div>

          <p class="press-header">About this job</p>

          <p class="light-text">
            YourBank is pleased to announce the introduction of our new Rewards
            Program, aimed at rewarding our loyal customers and enhancing their
            banking experience. The program offers exclusive benefits,
            discounts, and personalized offers tailored to individual customer
            preferences. With this initiative, YourBank reaffirms its commitment
            to delivering exceptional value and building lasting relationships
            with our valued customers.
          </p>

          <p class="press-header">Requirements & Qualifications</p>

          <div>
            <div class="flex mb-3">
              <GreyBriefLogo />
              <p class="light-text">
                Bachelor's degree in Business, Finance, or a related field
              </p>
            </div>
            <div class="flex mb-3">
              <GreyBriefLogo />
              <p class="light-text">
                Minimum of 2 years of experience in risk management or a similar
                role
              </p>
            </div>
            <div class="flex mb-3">
              <GreyBriefLogo />
              <p class="light-text">
                Bachelor's degree in Business, Finance, or a related field
              </p>
            </div>
            <div class="flex mb-3">
              <GreyBriefLogo />
              <p class="light-text">
                Bachelor's degree in Business, Finance, or a related field
              </p>
            </div>
          </div>

          <button class="btn primary mt-4">Apply</button>
        </div>
        <div class="press-card">
          <p class="press-header">Risk Analyst</p>

          <div>
            <span class="press-info">Location: India</span>
            <span class="press-info">Date: 06/11/2024</span>
          </div>

          <p class="press-header mt-5">About this job</p>

          <p class="light-text">
            YourBank is pleased to announce the introduction of our new Rewards
            Program, aimed at rewarding our loyal customers and enhancing their
            banking experience. The program offers exclusive benefits,
            discounts, and personalized offers tailored to individual customer
            preferences. With this initiative, YourBank reaffirms its commitment
            to delivering exceptional value and building lasting relationships
            with our valued customers.
          </p>

          <p class="press-header">Requirements & Qualifications</p>

          <div>
            <div class="flex mb-3">
              <GreyBriefLogo />
              <p class="light-text">
                Bachelor's degree in Business, Finance, or a related field
              </p>
            </div>
            <div class="flex mb-3">
              <GreyBriefLogo />
              <p class="light-text">
                Minimum of 3 years of experience in sales or relationship
                management in the banking industry
              </p>
            </div>
            <div class="flex mb-3">
              <GreyBriefLogo />
              <p class="light-text">
                Proven track record of meeting and exceeding sales targets
              </p>
            </div>
            <div class="flex mb-3">
              <GreyBriefLogo />
              <p class="light-text">
                Bachelor's degree in Business, Finance, or a related field
              </p>
            </div>
          </div>

          <button class="btn primary mt-4">Apply</button>
        </div>

        <div class="press-card">
          <div class="img-container-1"></div>

          <p class="press-header">IT Security Specialist</p>

          <div>
            <span class="press-info">Location: India</span>
            <span class="press-info">Date: 06/11/2024</span>
          </div>

          <p class="press-header mt-5">About this job</p>

          <p class="light-text">
            YourBank is pleased to announce the introduction of our new Rewards
            Program, aimed at rewarding our loyal customers and enhancing their
            banking experience. The program offers exclusive benefits,
            discounts, and personalized offers tailored to individual customer
            preferences. With this initiative, YourBank reaffirms its commitment
            to delivering exceptional value and building lasting relationships
            with our valued customers.
          </p>

          <p class="press-header">Requirements & Qualifications</p>

          <div>
            <div class="flex mb-3">
              <GreyBriefLogo />
              <p class="light-text">
                Bachelor's degree in Computer Science, Information Security, or
                a related fieldd
              </p>
            </div>
            <div class="flex mb-3">
              <GreyBriefLogo />
              <p class="light-text">
                Minimum of 3 years of experience in sales or relationship
                management in the banking industry
              </p>
            </div>
            <div class="flex mb-3">
              <GreyBriefLogo />
              <p class="light-text">
                In-depth knowledge of network security protocols and
                technologiess
              </p>
            </div>
            <div class="flex mb-3">
              <GreyBriefLogo />
              <p class="light-text">
                Bachelor's degree in Business, Finance, or a related field
              </p>
            </div>
          </div>
          <button class="btn primary">Apply</button>
        </div>
      </div>
    </main>

    <main>
      <h1 style="font-size: 38px">
        <span class="green-text">Frequently</span> Asked Questions
      </h1>
      <p class="light-text">
        Still you have any questions? Contact our Team via support@yourbank.com
      </p>

      <div class="grid grid-cols-2 gap-4 top-margin">
        <div class="faq-card">
          <p>How do I open an account with YourBank?</p>

          <div
            style="
              background: #262626;
              height: 2px;
              margin-bottom: 10px;
              margin-top: 10px;
            "
          ></div>

          <p class="light-text">
            Opening an account with YourBank is easy. Simply visit our website
            and click on the "Open an Account" button. Follow the prompts,
            provide the required information, and complete the application
            process. If you have any questions or need assistance, our customer
            support team is available to help.
          </p>
        </div>

        <div class="faq-card">
          <p>How do I open an account with YourBank?</p>

          <div
            style="
              background: #262626;
              height: 2px;
              margin-bottom: 10px;
              margin-top: 10px;
            "
          ></div>

          <p class="light-text">
            Opening an account with YourBank is easy. Simply visit our website
            and click on the "Open an Account" button. Follow the prompts,
            provide the required information, and complete the application
            process. If you have any questions or need assistance, our customer
            support team is available to help.
          </p>
        </div>

        <div class="faq-card">
          <p>How do I open an account with YourBank?</p>

          <div
            style="
              background: #262626;
              height: 2px;
              margin-bottom: 10px;
              margin-top: 10px;
            "
          ></div>

          <p class="light-text">
            Opening an account with YourBank is easy. Simply visit our website
            and click on the "Open an Account" button. Follow the prompts,
            provide the required information, and complete the application
            process. If you have any questions or need assistance, our customer
            support team is available to help.
          </p>
        </div>

        <div class="faq-card">
          <p>How do I open an account with YourBank?</p>

          <div
            style="
              background: #262626;
              height: 2px;
              margin-bottom: 10px;
              margin-top: 10px;
            "
          ></div>

          <p class="light-text">
            Opening an account with YourBank is easy. Simply visit our website
            and click on the "Open an Account" button. Follow the prompts,
            provide the required information, and complete the application
            process. If you have any questions or need assistance, our customer
            support team is available to help.
          </p>
        </div>
      </div>
    </main>
  </div>

  <FooterView />
</template>

<style>
@media (min-width: 1024px) {
}

.semi-big {
  font-size: 2.5rem;
}

.value-container {
  border-left: 1px solid var(--Green-60, #caff33);
  padding-left: 1.875rem;
}

.value-header {
  color: var(--Grey-30, #4c4c4d);
  font-size: 2.4rem;
  font-style: normal;
  font-weight: 500;
  line-height: 150%;
  /* 5.4375rem */
}

.value-text {
  color: var(--Grey-70, #b3b3b3);
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

.press-card > * {
  margin-bottom: 20px;
}

.press-header {
  line-height: 150%;
  font-size: 1.25rem;
  font-style: normal;
  font-weight: 400;
}

.press-info {
  color: var(--Grey-70, #b3b3b3);
  text-align: center;
  font-size: 1rem;
  font-style: normal;
  font-weight: 300;
  line-height: 150%;
  border-radius: 4.25rem;
  border: 1px solid var(--Grey-15, #262626);
  background: var(--Grey-10, #1a1a1a);
  padding: 0.375rem 0.875rem;
  margin-right: 10px;
}
</style>
