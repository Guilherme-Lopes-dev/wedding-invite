<template>
  <div class="main">
    <div class="fixed_text">
      <div class="names">
        <p class="name">Guilherme</p>
        <p class="">&</p>
        <p class="name">Andreza</p>
      </div>
      <div class="phrases">
        <p class="phrase">"A vida une as pessoas certas no momento certo.</p>
        <p class="phrase">Que esse seja nosso destino:</p>
        <p class="phrase">Amar, viver e começar cada dia juntos."</p>
        <div class="date">
          <p>09 de Março de 2024</p>
        </div>
      </div>
    </div>
    <div class="fixed">
      <img src="../assets/background.png" class="top_image" alt="" />
      <img src="../assets/background.png" class="bottom_image" alt="" />
    </div>
    <div class="scroll">
      <div class="arrow" style="display: none">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512">
          <!--!Font Awesome Free 6.5.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.-->
          <path
            d="M214.6 41.4c-12.5-12.5-32.8-12.5-45.3 0l-160 160c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0L160 141.2V448c0 17.7 14.3 32 32 32s32-14.3 32-32V141.2L329.4 246.6c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3l-160-160z"
          />
        </svg>
      </div>
      <div class="texts">
        <div class="text_top">
          <p class="text_inner">
            Convidamos você para este momento especial em que nossos corações se
            unirão em matrimônio. Temos a alegria de compartilhar o início da
            nossa nova jornada, juntos.
          </p>
        </div>
        <div class="text_mid">
          <p>Sábado, cerimônia às 17hs</p>
          <div class="date_container">
            <span> 09</span>
            <span class="span_svg">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                <!--!Font Awesome Free 6.5.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.-->
                <path
                  d="M47.6 300.4L228.3 469.1c7.5 7 17.4 10.9 27.7 10.9s20.2-3.9 27.7-10.9L464.4 300.4c30.4-28.3 47.6-68 47.6-109.5v-5.8c0-69.9-50.5-129.5-119.4-141C347 36.5 300.6 51.4 268 84L256 96 244 84c-32.6-32.6-79-47.5-124.6-39.9C50.5 55.6 0 115.2 0 185.1v5.8c0 41.5 17.2 81.2 47.6 109.5z"
                />
              </svg>
            </span>
            <span> Março</span>
            <span class="span_svg"
              ><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                <!--!Font Awesome Free 6.5.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.-->
                <path
                  d="M47.6 300.4L228.3 469.1c7.5 7 17.4 10.9 27.7 10.9s20.2-3.9 27.7-10.9L464.4 300.4c30.4-28.3 47.6-68 47.6-109.5v-5.8c0-69.9-50.5-129.5-119.4-141C347 36.5 300.6 51.4 268 84L256 96 244 84c-32.6-32.6-79-47.5-124.6-39.9C50.5 55.6 0 115.2 0 185.1v5.8c0 41.5 17.2 81.2 47.6 109.5z"
                /></svg
            ></span>
            <span>2024 </span>
          </div>
        </div>
        <div class="text_bottom">
          <p>Rua São Pedro, Chácara 105, Parque Maracanâ.</p>
        </div>
      </div>
      <div class="infos">
        <h2>Informações Importantes</h2>
        <details>
          <summary>Sobre os Presentes</summary>
          <p class="summary_content">
            Optamos por não fazer lista de presentes! Receberemos com o maior
            carinho o que você sentir no coração! Se preferir contribuir com
            nossa lua de mel, segue abaixo nossa chave pix! E caso não possa,
            não há problemas, o nosso presente é ter a sua companhia!
          </p>
        </details>
        <details>
          <summary>Como Chegar</summary>
          <p class="summary_content">
            O evento acontecerá em Goiânia/GO, Estrada 105, Chácaras Recreio São
            João, Goiânia - GO, 74470-140.
          </p>
        </details>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "home",
  setup() {
    return {};
  },
};
</script>
<style>
@import "./style.scss";

p {
  margin: 0;
}
.name {
  font-size: 82px;
  font-family: "The Amsterdam", sans-serif;
}

.phrase {
  text-align: center;

  font-family: "latian", sans-serif;
  font-size: 38px;
  font-weight: 400;
}
.date {
  font-family: "The Amsterdam", sans-serif;
  font-size: 32px;
}

.text_top {
  font-size: 32px;
}
.scroll {
  font-family: "latian", sans-serif;
}
.infos {
  font-family: "Montserrat", sans-serif;
}
b {
  font-size: 22px;
}
</style>
