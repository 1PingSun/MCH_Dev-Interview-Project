<template>
  <div class="introduction">
    <header class="intro-header">
      <div class="intro-img">
        <img src="https://1ping.org/src/profile-avatar.webp"/>
      </div>
      <div class="intro-text">
        <h2>自我介紹</h2>
        <p>
          我是孫逸平，目前就讀臺北市數位實驗高中，專長領域涵蓋資安、創客、急救、烏克麗麗和吉他等。 
        </p>
      </div>
        
      
    </header>
    <section class="about-section">
      <h3>個人資訊補充</h3>
      <ul>
        <li>好棒棒1</li>
        <li>好棒棒2</li>
        <li>好棒棒3</li>
      </ul>
      
    </section>
  </div>
</template>


<style scoped>
.introduction {
  padding: 40px 20px;
  max-width: 1200px;
  margin: 0 auto;
}

.intro-header {
  display: flex;
  flex-direction: row;
  background-color: #f5f5f5;
  padding: 40px;
  border-radius: 10px;
  gap: 20px;
}

.intro-img {
  width: 250px;
  height: 200px;
}

.intro-img img {
  width: 250px;
  height: 200px;
  object-fit: cover;
  border-radius: 5%;
}

.intro-text h2 {
  font-size: 2rem;
  margin-bottom: 20px;
}

.intro-text p {
  font-size: 1.1rem;
  margin-bottom: 20px;
}

.contact-button {
  padding: 10px 20px;
  background-color: #656d73;
  border: none;
  border-radius: 5px;
  color: #fff;
  cursor: pointer;
}

.contact-button:hover {
  background-color: #36383a;
}

.about-section {
  margin-top: 40px;
  padding: 0 40px;
}

.about-section h3 {
  font-size: 1.6rem;
  margin-top: 20px;
  margin-bottom: 10px;
}

.about-section p {
  font-size: 1rem;
  line-height: 1.6;
}
</style>
