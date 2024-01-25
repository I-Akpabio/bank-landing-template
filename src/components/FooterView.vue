<script setup>
import BankIcon from "./icons/BankIcon.vue"
import FacebookIcon from "./icons/FacebookIcon.vue"
import TwitterIcon from "./icons/TwitterIcon.vue"
import  LinkedinIcon from "./icons/LinkedinIcon.vue"
</script>
<template>
  <div style="padding: 3.7rem 2rem 1.88rem 2rem; background-color: #1c1c1c;">
    <div class="flex justify-center top-margin" style="margin-bottom: 2.5rem;">
      <BankIcon />
    </div>

    <div class="flex justify-center" style="margin-bottom: 2rem;">
      <a class="footer-a" href="">Home</a>
      <a class="footer-a" href="">Career</a>
      <a href="">About</a>
      <a href="">Security</a>
    </div>

    <div style="background: #262626; height: 2px; margin-bottom: 10px; margin-top: 10px;"></div>
    <div class="flex justify-center info">
      <span><svg width="21" height="20" viewBox="0 0 21 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path
            d="M1.75 7.22425V14.375C1.75 15.7557 2.86929 16.875 4.25 16.875H16.75C18.1307 16.875 19.25 15.7557 19.25 14.375V7.22425L11.8102 11.8026C11.0067 12.297 9.99327 12.297 9.18976 11.8026L1.75 7.22425Z"
            fill="#CAFF33" />
          <path
            d="M19.25 5.75652V5.625C19.25 4.24429 18.1307 3.125 16.75 3.125H4.25C2.86929 3.125 1.75 4.24429 1.75 5.625V5.75652L9.84488 10.738C10.2466 10.9852 10.7534 10.9852 11.1551 10.738L19.25 5.75652Z"
            fill="#CAFF33" />
        </svg>
        hello@skillbirdge.com
      </span>

      <span><svg width="21" height="20" viewBox="0 0 21 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path
            d="M1.75 7.22425V14.375C1.75 15.7557 2.86929 16.875 4.25 16.875H16.75C18.1307 16.875 19.25 15.7557 19.25 14.375V7.22425L11.8102 11.8026C11.0067 12.297 9.99327 12.297 9.18976 11.8026L1.75 7.22425Z"
            fill="#CAFF33" />
          <path
            d="M19.25 5.75652V5.625C19.25 4.24429 18.1307 3.125 16.75 3.125H4.25C2.86929 3.125 1.75 4.24429 1.75 5.625V5.75652L9.84488 10.738C10.2466 10.9852 10.7534 10.9852 11.1551 10.738L19.25 5.75652Z"
            fill="#CAFF33" />
        </svg>
        +91 91813 23 2309
      </span>

      <span><svg width="21" height="20" viewBox="0 0 21 20" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.1165 18.6259C10.1416 18.6405 10.1614 18.6517 10.1754 18.6596L10.1987 18.6726C10.3844 18.7745 10.6148 18.7738 10.8007 18.6729L10.8246 18.6596C10.8386 18.6517 10.8584 18.6405 10.8835 18.6259C10.9339 18.5967 11.0058 18.5542 11.0963 18.4985C11.2771 18.3872 11.5323 18.223 11.8372 18.0076C12.4459 17.5776 13.2581 16.9395 14.0721 16.1061C15.6922 14.4474 17.375 11.9551 17.375 8.75C17.375 4.95304 14.297 1.875 10.5 1.875C6.70304 1.875 3.625 4.95304 3.625 8.75C3.625 11.9551 5.30777 14.4474 6.92788 16.1061C7.74188 16.9395 8.55409 17.5776 9.16282 18.0076C9.46771 18.223 9.72295 18.3872 9.90375 18.4985C9.99419 18.5542 10.0661 18.5967 10.1165 18.6259ZM10.5 11.25C11.8807 11.25 13 10.1307 13 8.75C13 7.36929 11.8807 6.25 10.5 6.25C9.11929 6.25 8 7.36929 8 8.75C8 10.1307 9.11929 11.25 10.5 11.25Z" fill="#CAFF33"/>
</svg>

        Somewhere in the world
      </span>
    </div>

    <div style="background: #262626; height: 2px; margin-bottom: 10px; margin-top: 10px;"></div>


    <div class="flex justify-between footer-pill">
      <div>
        <FacebookIcon />
        <TwitterIcon />
        <LinkedinIcon />
</div>

      <p class="light-text">YourBank | All rights reserced</p>

      <p class="light-text">Privacy Policy | Terms Of Servce</p>
    </div>

  </div>
</template>

<style>
a {
  color: #E4E4E7;
font-family: Lexend;
font-size: 1rem;
font-style: normal;
font-weight: 300;
line-height: 150%; /* 1.5rem */
}
.light-text {
  color: var(--White-Shades-90, #E4E4E7);
font-family: Lexend;
font-size: 0.85rem;
font-style: normal;
font-weight: 300;
line-height: 150%; /* 1.5rem */
}
svg {
  display: inline;
  margin-right: 10px;
}

.info {
  padding: 3rem 0 3rem 0;
  background: var(--Grey-11, #1C1C1C);
}

.info span {
  margin-left: 1.2rem;
}
.footer-pill {
  border-radius: 6.25rem;
border: 1px solid var(--Grey-15, #262626);
background-color: #1a1a1a; padding: 0.75rem;
margin-top: 2.5rem;
}
</style>