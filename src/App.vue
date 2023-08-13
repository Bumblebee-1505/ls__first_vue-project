<script>
  import mainPage from "./components/mainPage.vue"

  export default {
    name: "App",
    components: {
      mainPage
    }
  }
</script>

<template>
  <mainPage/>
</template>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "inter";
  }

  .header {
    max-width: 1440px;
    background-color: #FAFAFA;
    margin: 0 auto;
    padding-bottom: 33px;
  }

  .header__container {
    max-width: 1200px;
    margin: 0 auto;
  }

  .container {
    max-width: 980px;
    margin: 0 auto;
  }

  .header__content {
    display: flex;
    justify-content: space-between;
    padding: 43.5px 0;
  }

  .header__nav_list {
    display: flex;
    align-items: center;
  }

  .header__nav-items {
    margin-left: 10px;
    list-style: none;
    margin-right: 10px;
  }

  .header__icons {
    display: flex;
    justify-content: space-between;
  }

  .header-icon {
    border: 2px solid #A6328D;
    border-radius: 50%;
    padding: 5px;
  }

  .header-name {
    margin-top: 10px;
    text-align: center;
    font-size: 12px;
    font-weight: 400;
  }

  /* Main */

  .main {
    max-width: 1440px;
    margin: 0 auto;
    padding-top: 8px;
  }

  .main__content {
    padding: 24px 0;
  }

  .main__content_header {
    display: flex;
    align-items: center;
    background-color: #FAFAFA;
    padding-bottom: 16px;
  }

  .main-image {
    width: 44px;
    height: 44px;
    margin-right: 14px;
  }

  .main__header-title{
    font-size: 18px;
    font-weight: 700;
  }

  .main__content_info {
    border-radius: 10px;
    border: 1px solid #F1F1F1;
    background: #FFF;
    box-shadow: 0px 4px 40px 0px rgba(0, 0, 0, 0.07);
    padding: 24px 20px;
  }

  .main__content_description {
    margin-bottom: 32px;
  }

  .main-title {
    margin-bottom: 15px;
    color: #292929;
    font-size: 26px;
    font-weight: 700;
  }

  .main-subtitle {
    color: #404040;
    font-size: 14px;
    font-weight: 400;
  }

  .main-subtitle span {
    font-weight: 700;
  }

  .main__content_info-block {
    display: flex;
  }

  .main__content_info-block div{
    color: #24292E;
    font-size: 14px;
    font-weight: 400;
  }

  /* .main-star::before {
    content: 
  } */

  .issues__description {
    display: flex;
  }

  .main__issues {
    padding: 10px 0;
  }

  .content-date {
    text-transform: uppercase;
  }

  .issues__description{
    padding-bottom: 6px;
  }

  .issues__description:nth-last-child() {
    padding: 0;
  }
</style>

