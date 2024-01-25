<script setup>
import Arrowleftright from "./icons/Arrowleftright.vue"
import IndianLogo from "./icons/IndianLogo.vue"
import USLogo from "./icons/USLogo.vue"
import BriefcaseLogo from "./icons/BriefcaseLogo.vue"
import ArrowLeft from "./icons/ArrowLeft.vue"
import QuoteIcon from "./icons/QuoteIcon.vue"
import ArrowRight from "./icons/ArrowRight.vue"
import NavBar from "./NavBar.vue"
import SavingLogo from "./icons/SavingLogo.vue"
import SmallGradientArrow from "./icons/SmallGradientArrow.vue"
import Bitcoin from "./icons/Bitcoin.vue"
</script>

<template>
  <div style="" class="container mx-auto px-8">
    <NavBar />
    <div class="grid grid-cols-2 hero-container gap-4">
      <div>
        <div class="flex nollc">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd" clip-rule="evenodd"
              d="M8.60288 3.79876C9.42705 2.85093 10.6433 2.25 12 2.25C13.3566 2.25 14.5728 2.85087 15.397 3.79861C16.6501 3.71106 17.9352 4.14616 18.8946 5.10557C19.854 6.06498 20.2891 7.35009 20.2016 8.60319C21.1492 9.42735 21.75 10.6435 21.75 12C21.75 13.3568 21.149 14.5731 20.2011 15.3973C20.2884 16.6502 19.8533 17.935 18.8941 18.8943C17.9348 19.8535 16.65 20.2886 15.3971 20.2013C14.5729 21.1491 13.3567 21.75 12 21.75C10.6434 21.75 9.4272 21.1491 8.60304 20.2014C7.34992 20.289 6.0648 19.8539 5.10537 18.8945C4.14596 17.935 3.71086 16.6499 3.79841 15.3968C2.85079 14.5726 2.25 13.3565 2.25 12C2.25 10.6434 2.85085 9.42723 3.79855 8.60306C3.7111 7.35005 4.14621 6.06507 5.10554 5.10574C6.06488 4.1464 7.34987 3.71129 8.60288 3.79876ZM15.6103 10.1859C15.8511 9.84887 15.773 9.38046 15.4359 9.1397C15.0989 8.89894 14.6305 8.97701 14.3897 9.31407L11.1543 13.8436L9.53033 12.2197C9.23744 11.9268 8.76256 11.9268 8.46967 12.2197C8.17678 12.5126 8.17678 12.9874 8.46967 13.2803L10.7197 15.5303C10.8756 15.6862 11.0921 15.7656 11.3119 15.7474C11.5316 15.7293 11.7322 15.6153 11.8603 15.4359L15.6103 10.1859Z"
              fill="#CAFF33" />
          </svg>
          <span>No LLC Required, No Credit Check.</span>

        </div>


        <h1 class="hero">Welcome to YourBank
          Empowering Your <span class="green-text">Financial Journey</span></h1>

        <p class="light-text">At YourBank, our mission is to provide comprehensive banking solutions that empower
          individuals and businesses
          to achieve their financial goals. We are committed to delivering personalized and innovative services that
          prioritize our customers' needs.</p>

        <button class="btn primary top-margin">Open Account</button>
      </div>
      <div style="max-width: 30rem; position: relative;">

        <div class="monthly-income">
          <svg width="39" height="39" viewBox="0 0 39 39" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect x="0.628906" y="0.379395" width="38.1496" height="38.1496" rx="19.0748" fill="#CAFF33" />
            <path fill-rule="evenodd" clip-rule="evenodd"
              d="M19.7036 13.6016C20.0627 13.6016 20.3538 13.8927 20.3538 14.2518V18.8038H24.9058C25.2649 18.8038 25.5561 19.0949 25.5561 19.4541C25.5561 19.8132 25.2649 20.1043 24.9058 20.1043H20.3538V24.6563C20.3538 25.0154 20.0627 25.3066 19.7036 25.3066C19.3444 25.3066 19.0533 25.0154 19.0533 24.6563V20.1043H14.5014C14.1422 20.1043 13.8511 19.8132 13.8511 19.4541C13.8511 19.0949 14.1422 18.8038 14.5014 18.8038L19.0533 18.8038V14.2518C19.0533 13.8927 19.3444 13.6016 19.7036 13.6016Z"
              fill="#1A1A1A" />
          </svg>

          <div>
            <p class="monthly-figure">+ $5000</p>
            <p class="monthly-label">Monthly Income</p>
          </div>

        </div>

        <div style="position: absolute; right: 6.87825rem; top: 6.875rem;">
          <div class="arrows-container" style="position: absolute; top: 8rem; left: -3rem; opacity: 0.5;">
            <svg xmlns="http://www.w3.org/2000/svg" width="226" height="225" viewBox="0 0 226 225" fill="none">
              <path
                d="M161.703 13.4457L161.326 2.83418L225.013 0.502441L222.71 64.2274L212.088 63.8504L213.721 19.3379L8.41082 224.727L0.901855 217.215L206.226 11.8121L161.703 13.4457Z"
                fill="url(#paint0_linear_5_86809)" style="mix-blend-mode:screen" />
              <defs>
                <linearGradient id="paint0_linear_5_86809" x1="200.766" y1="-13.5009" x2="49.4495" y2="248.439"
                  gradientUnits="userSpaceOnUse">
                  <stop offset="0.11" stop-color="#CAFF33" />
                  <stop offset="1" stop-color="#191919" stop-opacity="0" />
                </linearGradient>
              </defs>
            </svg>
          </div>
          <div class="arrows-container" style="position: absolute;  opacity: 0.5;">
            <svg xmlns="http://www.w3.org/2000/svg" width="226" height="225" viewBox="0 0 226 225" fill="none">
              <path
                d="M161.703 13.4457L161.326 2.83418L225.013 0.502441L222.71 64.2274L212.088 63.8504L213.721 19.3379L8.41082 224.727L0.901855 217.215L206.226 11.8121L161.703 13.4457Z"
                fill="url(#paint0_linear_5_86809)" style="mix-blend-mode:screen" />
              <defs>
                <linearGradient id="paint0_linear_5_86809" x1="200.766" y1="-13.5009" x2="49.4495" y2="248.439"
                  gradientUnits="userSpaceOnUse">
                  <stop offset="0.11" stop-color="#CAFF33" />
                  <stop offset="1" stop-color="#191919" stop-opacity="0" />
                </linearGradient>
              </defs>
            </svg>
          </div>

          <div class="arrows-container" style="position: absolute;  top: 10.1rem; left: 12.6rem; opacity: 0.5;">
            <SmallGradientArrow />
          </div>
          <div class="arrows-container" style="position: absolute; top: 10.5rem; left: 8.5rem; opacity: 0.5;">
            <svg xmlns="http://www.w3.org/2000/svg" width="80" height="79" viewBox="0 0 80 79" fill="none">
              <path
                d="M56.978 4.55123L56.8478 0.849249L79.0385 0.0366211L78.237 22.2686L74.5402 22.1382L75.1013 6.60789L3.56011 78.2498L0.945312 75.6313L72.4865 3.98942L56.978 4.55123Z"
                fill="url(#paint0_linear_104_621)" style="mix-blend-mode:screen" />
              <defs>
                <linearGradient id="paint0_linear_104_621" x1="70.5896" y1="-4.84799" x2="17.7807" y2="86.4738"
                  gradientUnits="userSpaceOnUse">
                  <stop offset="0.11" stop-color="#CAFF33" />
                  <stop offset="1" stop-color="#191919" stop-opacity="0" />
                </linearGradient>
              </defs>
            </svg>
          </div>

          <div class="arrows-container" style="position: absolute; left: 5rem; opacity: 0.5;">
            <SmallGradientArrow />
          </div>
          <div class="arrows-container" style="position: absolute; top: 4.9rem; left:11rem; opacity: 0.5;">
            <SmallGradientArrow />
          </div>
        </div>


        <div class="hero-right" style="padding: 2.1rem; margin: 3rem 0 0 3rem;">
          <p class="mb-5">Your Transaction</p>

          <div class="flex justify-between transact-row row-1" style="z-index: 6; position: relative;">
            <div class="flex justify-between">
              <Arrowleftright />
              <div class="ml-3">
                <p class="trasaction-label">Transcation</p>
                <p class="trasaction-name">John Thomas</p>
              </div>

            </div>

            <span class="transaction-amount">-$68.00</span>
          </div>
          <div class="flex justify-between transact-row row-2">
            <div class="flex justify-between">
              <Arrowleftright />
              <div class="ml-3">
                <p class="trasaction-label">Transcation</p>
                <p class="trasaction-name">Mark Smith</p>
              </div>

            </div>

            <span class="transaction-amount">-$68.00</span>
          </div>
          <div class="flex justify-between transact-row row-3">
            <div class="flex justify-between">
              <Arrowleftright />
              <div class="ml-3">
                <p class="trasaction-label">Transcation</p>
                <p class="trasaction-name">Lennen Roy</p>
              </div>

            </div>

            <span class="transaction-amount">-$68.00</span>
          </div>

          <p class="my-6">Money Exchange</p>
          <div class="grid grid-cols-2" style="background-color: #1C1C1C; border-radius: 0.5165rem;border: 0.689px solid var(--Grey-15, #262626);">
            <div style="padding: 0.86rem;">
              <div class="flex items-center mb-3">
                <IndianLogo class="mr-3" />

                <p>INR</p>
              </div>
              <p style="font-weight: 300;">Indian Rupees</p>
            </div>

            <div style="padding: 0.86rem;">
              <div class="flex items-center mb-3">
                <img class="mr-3" src="/images/us-logo.png" />
                <p>USD</p>
              </div>
              <p style="font-weight: 300;">United States Dollars</p>
            </div>

            <div style="padding: 1.29rem 0.86rem;">
              <p>5,000</p>
            </div>
            <div style="padding: 1.29rem 0.86rem;">
              <p>12.0</p>
            </div>
          </div>

          <button class="btn exchange">Exchange</button>
        </div>

      </div>

    </div>

    <div class="flex flex-row-reverse mt-6">
      <div
        style="display: flex; align-items: center; border-radius: 4.33519rem; padding: 0.5rem 1.3rem;background: #22251B;">
        Supported Currency

        <div class="supported-icons">
          <Bitcoin />
          <svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path
              d="M35.352 17.6875C35.352 27.2141 27.6294 34.9369 18.1029 34.9369C8.57626 34.9369 0.853516 27.2141 0.853516 17.6875C0.853516 8.16098 8.57626 0.438232 18.1029 0.438232C27.6293 0.438232 35.352 8.16098 35.352 17.6875Z"
              fill="#262626" />
            <path
              d="M22.9504 24.8947L22.5524 23.0873C22.5298 22.981 22.4729 22.9014 22.3818 22.8486C22.2833 22.7954 22.1848 22.788 22.0864 22.8259L22.0294 22.8486L21.8928 22.8826C21.8321 22.8976 21.762 22.9148 21.6825 22.9337C21.6029 22.9526 21.5102 22.9714 21.404 22.9905C21.2982 23.0095 21.1859 23.0266 21.0687 23.0418C20.9513 23.0566 20.8246 23.0701 20.688 23.0815C20.5515 23.0927 20.4152 23.0985 20.2787 23.0985C19.3161 23.0985 18.4501 22.839 17.681 22.3198C16.9117 21.8005 16.3452 21.0976 15.9814 20.211H20.3808C20.4643 20.211 20.5401 20.1827 20.608 20.1257C20.6765 20.069 20.7182 19.999 20.733 19.9153L21.0059 18.642C21.0287 18.5287 21.0059 18.4262 20.9378 18.3352C20.8621 18.2442 20.7671 18.1986 20.6536 18.1986H15.4358C15.4131 17.6833 15.4131 17.2854 15.4358 17.005H20.9835C21.1883 17.005 21.3094 16.9065 21.3473 16.7095L21.6201 15.4135C21.6427 15.3074 21.6166 15.209 21.5405 15.1179C21.4726 15.027 21.3778 14.9813 21.2565 14.9813H15.9361C16.315 14.1325 16.8834 13.4656 17.6414 12.9806C18.3993 12.4954 19.2557 12.2529 20.2106 12.2529C20.241 12.2378 20.3527 12.2416 20.5458 12.2643C20.739 12.2869 20.8491 12.2965 20.8755 12.2927C20.9017 12.2889 21.0006 12.3004 21.171 12.3267C21.3416 12.3532 21.4269 12.3665 21.4269 12.3665L21.6258 12.4063C21.6828 12.4177 21.7264 12.4271 21.7566 12.4347L21.8021 12.446C21.9006 12.4765 21.9913 12.4669 22.075 12.4177C22.1584 12.3683 22.2115 12.2945 22.2343 12.196L22.7232 10.3885C22.7458 10.2899 22.7343 10.199 22.6891 10.1157C22.6208 10.0246 22.5449 9.96773 22.4616 9.94508C21.7644 9.7708 21.0289 9.68359 20.2561 9.68359C18.5582 9.68359 17.0407 10.1688 15.703 11.1387C14.3653 12.1088 13.4426 13.3897 12.9348 14.9812H11.8208C11.7146 14.9812 11.6275 15.0153 11.5593 15.0835C11.4912 15.1516 11.457 15.2388 11.457 15.345V16.6409C11.457 16.747 11.4911 16.8342 11.5593 16.9023C11.6276 16.9706 11.7148 17.0045 11.8208 17.0045H12.5825C12.5596 17.3684 12.556 17.7661 12.571 18.1983H11.8208C11.7223 18.1983 11.637 18.2343 11.565 18.3063C11.4931 18.3782 11.457 18.4635 11.457 18.5619V19.8466C11.457 19.9452 11.4931 20.0303 11.565 20.1025C11.637 20.1745 11.7223 20.2101 11.8208 20.2101H12.9008C13.3782 21.8851 14.2802 23.2172 15.6065 24.2062C16.9329 25.1955 18.4827 25.6898 20.2561 25.6898C20.4002 25.6898 20.546 25.6863 20.6939 25.6784C20.842 25.6708 20.9801 25.6593 21.1089 25.6443C21.2377 25.6293 21.3647 25.6124 21.4898 25.5934C21.6148 25.5743 21.7285 25.5557 21.8307 25.5364C21.9331 25.5176 22.0297 25.4987 22.1206 25.4799C22.2116 25.4607 22.2931 25.4401 22.3652 25.4172C22.4371 25.3947 22.4975 25.3775 22.5469 25.3664C22.5963 25.3549 22.636 25.3414 22.6661 25.3266L22.7231 25.3151C22.8065 25.2849 22.871 25.2298 22.9164 25.1501C22.9619 25.071 22.973 24.9856 22.9504 24.8947Z"
              fill="#CAFF33" />
          </svg>

        </div>

      </div>
    </div>
  </div>




  <div style="" class="container mx-auto px-20 2xl:px-40">
    <main>
      <h1 style="font-size: 38px;">Our <span class="green-text"> Products</span></h1>

      <div class="flex justify-between">
        <p style="width: 700px;" class="light-text">Discover a range of comprehensive and customizable banking products at
          YourBank, designed
          to suit your unique
          financial needs and aspirations</p>

        <div style="border-radius: 5.125rem;
        padding: 0.875rem;
        border: 1px solid var(--Grey-15, #262626);
        background: var(--Grey-11, #1C1C1C);">
          <button class="mr-3 btn-primary-small">For Individual</button>
          <button>For Business</button>
        </div>
      </div>

      <div class="grid grid-cols-3 gap-4" style="margin-top: 3rem;">


        <div class="flex flex-col items-center pr-10" style="border-right: 1px solid #262626;">
          <BriefcaseLogo />


          <p class="mb-4">Checking Accounts</p>
          <p class="light-text text-center">Enjoy easy and convenient access to your funds with our range of checking
            account options. Benefit from
            features such as online and mobile banking, debit cards, and free ATM access.</p>
        </div>


        <div class="flex flex-col items-center pr-10 pl-5" style="border-right: 1px solid #262626;">
          <BriefcaseLogo />


          <p class="mb-4">Saving Accounts</p>
          <p class="light-text text-center">Enjoy easy and convenient access to your funds with our range of checking
            account options. Benefit from
            features such as online and mobile banking, debit cards, and free ATM access.</p>
        </div>


        <div class="flex flex-col items-center pl-8">
          <BriefcaseLogo />


          <p class="mb-4">Loan and Mortages</p>
          <p class="light-text text-center">Enjoy easy and convenient access to your funds with our range of checking
            account options. Benefit from
            features such as online and mobile banking, debit cards, and free ATM access.</p>
        </div>

      </div>


    </main>

    <main>
      <h1 style="font-size: 38px;" class="green-text">Use Cases</h1>
      <p class="light-text">At YourBank, we cater to the diverse needs of individuals and businesses alike, offering a
        wide range of
        financial solutions</p>

      <div class="grid grid-cols-2 gap-4" style="margin-top: 3rem;">

        <div class="grid grid-cols-2 gap-4 cases-grid" style="margin-right: 2rem;">
          <div class="cases-item flex flex-col items-center">
            <BriefcaseLogo />
            <p class="text-center">Managing Personal Finances</p>
          </div>

          <div class="cases-item flex flex-col items-center">
            <SavingLogo />
            <p>Saving for the Future</p>
          </div>

          <div class="cases-item flex flex-col items-center">
            <BriefcaseLogo />
            <p>HomeOwnership</p>
          </div>

          <div class="cases-item flex flex-col items-center">
            <BriefcaseLogo />
            <p>Education Funding</p>
          </div>
        </div>

        <div>
          <p style="font-size: 1.5rem; font-weight: 500;">For Individual</p>

          <p class="light-text">For individuals, our mortgage services pave the way to homeownership, and our flexible
            personal loans provide vital support during various life milestones. We also prioritize retirement planning,
            ensuring a financially secure future for our customers</p>

          <div class="grid grid-cols-3" style="margin-top: 4rem;">
            <div style="border-right: 1px dashed #262626; margin-right: 16px;">
              <p class="big-number">78%</p>
              <p class="light-text">Secure Retirement Planning</p>
            </div>

            <div style="border-right: 1px dashed #262626; margin-right: 16px;">
              <p class="big-number">63%</p>
              <p class="light-text">Secure Retirement Planning</p>
            </div>

            <div>
              <p class="big-number">91%</p>
              <p class="light-text">Reducing financial burdens</p>
            </div>

          </div>
          <button class="mt-4 btn-dark">Learn More</button>
        </div>

        <div>
          <p style="font-size: 1.5rem; font-weight: 500;">For Business</p>

          <p class="light-text">For individuals, our mortgage services pave the way to homeownership, and our flexible
            personal loans provide vital support during various life milestones. We also prioritize retirement planning,
            ensuring a financially secure future for our customers</p>

          <div class="grid grid-cols-3" style="margin-top: 4rem;">
            <div>
              <p class="big-number">65%</p>
              <p class="light-text">Secure Retirement Planning</p>
            </div>

            <div>
              <p class="big-number">70%</p>
              <p class="light-text">Secure Retirement Planning</p>
            </div>

            <div>
              <p class="big-number">45%</p>
              <p class="light-text">Reducing financial burdens</p>
            </div>

          </div>
          <button class="mt-4">Learn More</button>
        </div>

        <div class="grid grid-cols-2 gap-3 cases-grid curved">
          <div class="cases-item flex flex-col items-center">
            <BriefcaseLogo />
            <p>Startups and Entrepreneurs</p>
          </div>

          <div class="cases-item flex flex-col items-center">
            <BriefcaseLogo />
            <p>Saving for the Future</p>
          </div>

          <div class="cases-item flex flex-col items-center">
            <BriefcaseLogo />
            <p>HomeOwnership</p>
          </div>

          <div class="cases-item flex flex-col items-center">
            <BriefcaseLogo />
            <p>Education Funding</p>
          </div>
        </div>
      </div>



    </main>

    <main>
      <h1 style="font-size: 38px;">Our <span class="green-text">Features</span></h1>
      <p class="light-text">At YourBank, we cater to the diverse needs of individuals and businesses alike, offering a
        wide range of
        financial solutions</p>

      <div class="grid grid-cols-5 top-margin gap-4">

        <div class="feature-card">
          <a class="active" href="">Online bank</a>
          <a href="">Financial Tools</a>
          <a href="">Customer Support</a>
        </div>

        <div class="col-span-4">
          <div class="grid grid-cols-2 gap-4">
            <div class="feature-card border">
              <div class="flex justify-between">
                <p>24/7 Account Access</p>

                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M8.50007 26.9166L26.9167 8.49994M26.9167 8.49994V26.1799M26.9167 8.49994H9.23673"
                    stroke="#CAFF33" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
                </svg>

              </div>

              <p class="light-text">Enjoy the convenience of accessing your accounts anytime, anywhere through our secure
                online banking platform. Check balances, transfer funds, and pay bills with ease.</p>
            </div>

            <div class="feature-card border">
              <div class="flex justify-between">
                <p>Mobile Banking App</p>

                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M8.50007 26.9166L26.9167 8.49994M26.9167 8.49994V26.1799M26.9167 8.49994H9.23673"
                    stroke="#CAFF33" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
                </svg>

              </div>

              <p class="light-text">Enjoy the convenience of accessing your accounts anytime, anywhere through our secure
                online banking platform. Check balances, transfer funds, and pay bills with ease.</p>
            </div>

            <div class="feature-card border">
              <div class="flex justify-between">
                <p>Secure Transactions</p>

                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M8.50007 26.9166L26.9167 8.49994M26.9167 8.49994V26.1799M26.9167 8.49994H9.23673"
                    stroke="#CAFF33" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
                </svg>

              </div>

              <p class="light-text">Enjoy the convenience of accessing your accounts anytime, anywhere through our secure
                online banking platform. Check balances, transfer funds, and pay bills with ease.</p>
            </div>

            <div class="feature-card border">
              <div class="flex justify-between">
                <p>Bill pay and Transfers</p>

                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M8.50007 26.9166L26.9167 8.49994M26.9167 8.49994V26.1799M26.9167 8.49994H9.23673"
                    stroke="#CAFF33" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
                </svg>

              </div>

              <p class="light-text">Enjoy the convenience of accessing your accounts anytime, anywhere through our secure
                online banking platform. Check balances, transfer funds, and pay bills with ease.</p>
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
    </main>

    <main>
      <h1 style="font-size: 38px;">Our <span class="green-text">Testimonials</span></h1>

      <div class="flex justify-between">
        <p style="width: 700px;" class="light-text">Discover a range of comprehensive and customizable banking products at
          YourBank, designed to suit your unique
          financial needs and aspirations</p>
        <div>
          <button class="mr-3 btn-primary-small">For Individual</button>
          <button>For Business</button>
        </div>

      </div>

      <div class="flex mt-5">
        <div>
          <ArrowLeft />
        </div>

        <div class="grow">

          <div class="flex">

            <div class="flex">
              <div class="testimonial-card">
                <div class="flex justify-center">
                  <QuoteIcon />
                </div>


                <p class="mt-5">I recently started my own business, and YourBank has been instrumental in helping me set
                  up
                  my business
                  accounts and secure the financing I needed. Their expert guidance and tailored solutions have been
                  invaluable.</p>

                <p class="green-text text-center">
                  John D
                </p>
              </div>
            </div>

            <div class="flex">
              <div class="testimonial-card">
                <div class="flex justify-center">
                  <QuoteIcon />
                </div>


                <p class="mt-5">I recently started my own business, and YourBank has been instrumental in helping me set
                  up
                  my business
                  accounts and secure the financing I needed. Their expert guidance and tailored solutions have been
                  invaluable.</p>

                <p class="green-text text-center">
                  John D
                </p>
              </div>
            </div>

            <div class="flex">
              <div class="testimonial-card">
                <div class="flex justify-center">
                  <QuoteIcon />
                </div>


                <p class="mt-5">I recently started my own business, and YourBank has been instrumental in helping me set
                  up
                  my business
                  accounts and secure the financing I needed. Their expert guidance and tailored solutions have been
                  invaluable.</p>

                <p class="green-text text-center">
                  John D
                </p>
              </div>
            </div>


          </div>

        </div>


        <ArrowRight />


      </div>
    </main>

    <main
      style="border-radius: 1.25rem;border: 1px solid #262626;background: #1C1C1C;background-blend-mode: normal, screen, normal; padding: 3.75rem;">
      <div class="flex justify-between">
        <div style="max-width: 70%">
          <h1 style="font-size: 1.8rem;">Start your financial journey with <span class="green-text">YourBank today</span>
          </h1>
          <p class="light-text">Ready to take control of your finances? Join YourBank now, and let us help you achieve
            your financial goals with our tailored solutions and exceptional customer service</p>
        </div>

        <button class="btn-primary-small">Open Account</button>
      </div>
    </main>

  </div>
</template>

<style>
nav {
  margin: 2em 0 2rem 0;
}

a {
  margin-right: 10px;
}


.nollc {
  border-radius: 61px;
  background: var(--Grey-15, #262626);
  padding: 0.625rem 1.25rem 0.625rem 0.75rem;
  max-width: 22rem;

}

.nollc span {
  font-weight: 300;
}

.monthly-income {
  position: absolute;
  border-radius: 0.65025rem;
  background: #22251B;
  padding: 0.86706rem 1.08381rem;
  display: flex;

}

.monthly-figure {
  color: var(--Absolute-White, #FFF);
  font-size: 0.98381rem;
  font-style: normal;
  font-weight: 400;
  line-height: 150%;
  /* 1.62569rem */
}

.monthly-label {
  color: var(--White-90, #E4E4E7);
  font-size: 0.76706rem;
  font-style: normal;
  font-weight: 300;
  line-height: 150%;
  /* 1.30056rem */
}

h1.hero {
  color: var(--Absolute-White, #FFF);
  font-family: 'Lexend';
  font-size: 48px;
  font-style: normal;
  font-weight: 500;
  line-height: 150%;
  /* 72px */
}

.hero-container {
  margin-top: 5rem;
}

.hero-right {
  border-radius: 0.65025rem;
  border: 0.867px solid #262626;
  background: linear-gradient(215deg, rgba(26, 26, 26, 0.00) 0%, #1A1A1A 39.72%), url(<path-to-image>), lightgray 0% 0% / 62.46418356895447px 62.46418356895447px repeat, #1A1A1A;
  background-blend-mode: normal, screen, normal;
}

.trasaction-label {
  color: var(--Absolute-White, #FFF);
  font-size: 16.396px;
  font-style: normal;
  font-weight: 300;
  line-height: 150%;
}

.trasaction-name {
  color: var(--Absolute-White, #FFF);
  font-size: 17.773px;
  font-style: normal;
  font-weight: 400;
  line-height: 150%;
  /* 20.66px */
}

.transaction-amount {
  color: var(--Absolute-White, #FFF);
  font-size: 17.396px;
  margin-top: 27px;
  font-style: normal;
  font-weight: 500;
  line-height: 150%;
}

p.light-text {
  color: var(--Grey-70, #B3B3B3);
  font-size: 15px;
  font-style: normal;
  font-weight: 300;
  line-height: 150%;
}

.big-number {
  color: var(--Green-60, #CAFF33);
  font-size: 58px;
  font-style: normal;
  font-weight: 500;
  line-height: 150%;
  /* 87px */
}

.cases-grid {
  background-color: #1C1C1C;
  padding: 2.5rem;
}

.cases-item {
  border-radius: 1rem;
  border: 1px solid var(--Grey-15, #262626);
  background: var(--Grey-10, #1A1A1A);
  padding: 1.5rem;
}


.testimonial-card {
  width: 20.8rem;
  height: 18.18rem;
}

.transact-row {
  border-radius: 0.5165rem;
  border: 0.689px solid var(--Grey-15, #262626);
  background-color: #1C1C1C;
  padding: 0.69rem 1.03rem;
}

.transact-row.row-2 {
  opacity: 0.5;
  margin: -1.1rem 0.86rem 0rem 0.86rem;
  z-index: 4;
  position: relative;
}

.transact-row.row-3 {
  opacity: 0.2;
  margin: -1.1rem 1.72rem 0 1.72rem;
  z-index: 2;
  position: relative;
}


nav a {
  color: var(--Absolute-White, #FFF);
  font-size: 0.875rem;
  font-style: normal;
  font-weight: 400;
  line-height: 150%;
  /* 1.3125rem */
}

.bg-second-grey {
  background-color: #1C1C1C;
}

.feature-card {
  background-color: #1C1C1C;
  padding: 2.3rem;
  border-radius: 0.625rem;
}

.feature-card.border {
  border: 1px solid var(--Grey-15, #262626);
}

.feature-card a {
  display: block;
  padding: 0.775rem 1.25rem;
  border-radius: 6.25rem;
  border: 1px solid var(--Grey-15, #262626);
  margin-bottom: 1rem;
  font-size: 0.75rem;
}

.feature-card a.active {
  display: block;
  padding: 0.775rem 1.25rem;
  border-radius: 6.25rem;
  color: var(--Green-60, #CAFF33);
  font-weight: 400;
  border: 1px solid var(--Grey-15, #262626);
  background: var(--Grey-10, #1A1A1A);
  margin-bottom: 1rem;
  font-size: 0.75rem;
}

.supported-icons {
  padding: 0.54188rem;
  border-radius: 2.98044rem;
  border: 0.867px solid var(--Grey-15, #262626);
  background: var(--Grey-10, #1A1A1A);
}</style>