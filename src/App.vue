<script setup>
  import { ref } from 'vue';
  const blogPage = ref(false)
  const postPage = ref(false)
  const homePage = ref(true)


  const readPost = () =>{
    blogPage.value = false;
    postPage.value = true;
  }

</script>

<template>
  <div class="wrapper">
    <header class="header">
      <h1>НИКИТА СУСЛОВ</h1>
    </header>
    <nav class="navigation">
      <ul>
        <li>ОБО МНЕ</li>
        <li>БЛОГ</li>
        <li>ДИЗАЙН</li>
        <li>ПРОЕКТЫ</li>
        <li>КОНТАКТЫ</li>
      </ul>
    </nav>
      <main v-show = "homePage">
      <div class="about">
        <div class="photo">
          <img class="my-photo" src="/src/assets/images/photo_2024-09-16_02-32-52.jpg" alt="my_photo.jpg">
        </div>
        <div class="about-me">
          <h1>Веб-разработка</h1>
          <p>Привет! Меня зовут Никита. Я не имею IT образования, но уже два года активно занимаюсь программированием. За это время я изучал различные языки программирования, включая Python, C++, и Scheme. Особенно меня увлекает компьютерная наука как область исследований. В настоящее время я сосредоточен на изучении Vue 3 и работе над своим PET проектом. Кроме того, я планирую вести блог, где буду делиться своим опытом и путешествием в мире веб-разработки. В свободное время я наслаждаюсь игрой в MTG и всегда готов к новым вызовам в программировании. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eos eveniet expedita in distinctio dignissimos odit! Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nam itaque, quae magni laboriosam reprehenderit minus minima quasi error aspernatur, tempora quisquam adipisci, distinctio id molestias?</p>
        </div>
      </div>
      <div class="lifestyle">
        <h1>Моя жизнь</h1>
        <p>Также я активно веду соцсети, где показываю как я отдыхаю, путешествую и просто гуляю. Я всегда открыт к новым знакомствам и людям. Подписывайся на мои соцчсети внизу страницы, и елси что пиши, сегда буду рад. Обнял.</p>
        <div>Картинки</div>
        <div>Картинки</div>
        <div>Картинки</div>
      </div>
    </main>
  </div>
  
  <section v-show="postPage" class="postPage">
    <h1>Заголовок</h1>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Commodi esse laborum maxime quas. Neque id quidem fugiat placeat facilis nemo praesentium laboriosam dolorum. Ratione illum voluptate veritatis et asperiores voluptatibus minus natus ut corporis quo? Modi et incidunt tempore molestias aliquam autem, temporibus labore ad cupiditate recusandae consectetur quos doloremque voluptas sunt mollitia odit repellendus iure suscipit? Maiores, facere impedit assumenda, cum molestias, rerum error excepturi fugiat veniam consequuntur perspiciatis esse possimus velit quae minima nihil. Praesentium nisi, temporibus magni perspiciatis laborum id natus repudiandae incidunt saepe magnam reiciendis eligendi sit distinctio voluptatem. Aliquam corrupti aut provident quaerat, eum corporis natus et dignissimos aliquid hic magni enim temporibus nostrum animi placeat aspernatur suscipit accusamus quos architecto aperiam. Rem, natus! Dicta eos saepe alias voluptatem. Obcaecati tempora dicta ut perferendis officia dolore, error quis maiores omnis, hic officiis voluptate in illo doloremque quisquam consequatur. Dolorem eaque ex nisi, rerum, commodi fugit ut delectus id officia expedita unde doloribus possimus excepturi minus minima tempore error, officiis quasi harum saepe! Numquam quidem reiciendis optio autem assumenda. Eaque mollitia necessitatibus quibusdam similique molestias asperiores cumque, iusto laudantium, ea recusandae culpa repudiandae a ad nam ipsum quisquam voluptatem hic, placeat officia totam cupiditate laboriosam itaque eligendi architecto! Esse delectus odio facere dolorum natus architecto reprehenderit culpa, hic voluptate sed quaerat, officia velit minus perferendis illum magni, autem iste. Quaerat commodi illo nisi? Facere dolor temporibus voluptatibus dolores quis minima soluta? Maxime non repellat doloremque vel magni, ad necessitatibus, qui explicabo incidunt numquam amet, et eos natus. Sint, tempora et numquam temporibus autem, non doloribus repudiandae quod, nemo dicta ipsum. Fugit at accusantium incidunt nam porro consequatur nesciunt atque ut voluptas est, sequi hic? Eius a mollitia, obcaecati quos ratione voluptatum! Consequuntur recusandae deleniti iste quos ex laudantium debitis! Sed officia, tempore impedit ut iste veritatis aperiam enim maiores ex consequuntur dignissimos beatae perspiciatis architecto maxime odio, animi nulla, iure quasi libero at inventore! Velit iusto delectus accusamus nesciunt deserunt, blanditiis illum amet fugiat, ut maiores eveniet, id tenetur architecto rem. Est earum, molestiae veritatis exercitationem nam at tenetur dolorum aliquam voluptatum ullam vitae illum? Doloremque impedit natus ab explicabo odit molestias porro eum consequuntur doloribus deserunt dolores, nisi numquam reiciendis blanditiis veniam quasi ut saepe perspiciatis soluta quisquam! Dolorem aliquid accusamus veniam sed accusantium, doloribus, repudiandae officia omnis reiciendis expedita eos! Laboriosam temporibus delectus esse soluta quos aliquid labore itaque hic! Magni pariatur ab, similique sequi, dolore beatae tempore enim in labore iusto laborum, animi reiciendis excepturi. Modi aliquid rerum eveniet ex perspiciatis magni, alias assumenda. Impedit quia, quaerat, quidem asperiores eligendi adipisci officia nam assumenda labore iste facilis obcaecati! Nam ea distinctio accusantium et nostrum incidunt eos provident atque, explicabo magnam iste voluptates nobis delectus commodi facilis inventore voluptatibus earum obcaecati neque, reiciendis maxime temporibus veritatis libero consequatur. Delectus itaque molestiae doloribus laborum consequatur eum ullam omnis, voluptas veritatis quasi odit vero doloremque optio illum at dignissimos iste! Laboriosam obcaecati perferendis deleniti amet? Obcaecati doloremque saepe tempora. Non pariatur, qui quisquam quo esse impedit?</p>
  </section>

  <main v-show = "blogPage" class="blog">
    <div class="wraper">
      <div class="post" @click="readPost">
        <h1>Как я изучаю Vue 3</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos, modi nemo tenetur expedita aliquam beatae, voluptate rerum optio voluptatibus quae ipsum a quidem officiis doloremque qui explicabo ex. Rerum ipsam in iste laborum corrupti ducimus quibusdam eaque voluptates? Voluptas quibusdam voluptatem nobis repellendus velit nam eius tempore consectetur perspiciatis unde.</p>
        <span>16.09.24</span>
      </div>
      <div class="post">
        <h1>Заголовок</h1>
        <p>Описание</p>
        <span>Дата создания</span>
      </div>
      <div class="post">
        <h1>Заголовок</h1>
        <p>Описание</p>
        <span>Дата создания</span>
      </div>
      <div class="post">
        <h1>Заголовок</h1>
        <p>Описание</p>
        <span>Дата создания</span>
      </div>
    </div>
  </main>
  <footer class="footer">
    
  </footer>
</template>

<style scoped>
  .wrapper{
    max-width: 1280px;
    margin: 0 auto;
    display: flex;
    align-items: center;
    flex-direction: column;
    gap: 3rem;
  }

  .header{
    max-width: 1080px;
    margin: 0 auto;
    text-align: center;
  }
  
  .navigation {
    margin-top: 1rem;
    font-size: 16px;
  }

  .navigation ul{
    display: flex;
    gap: 3rem;
    list-style: none;
  }

  .about {
    max-width: 1080px;
    margin: 0 auto;
    margin-top: 5rem;
    display: flex;
    justify-content: space-around;
    gap: 1rem;
  }

  .photo {
    height: 600px;
  }

  .my-photo{
    height: 100%;
  }

  .about-me{
    width: 30%;
  }

  .lifestyle{
    margin-top: 3rem;
    margin: 0 auto;
    max-width: 1080px;
  }
  .footer{
    display: none;
    background-color: rgb(250, 250, 241);
    height: 400px;
  }

  .blog .wraper{
    justify-content: center;
    margin-top: 5rem;
    display: flex;
    flex-wrap:wrap;
    gap: 5rem;
  }

  .post{
    display: flex;
    padding: 20px;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    border: 1px solid black;
    border-radius: 10px;
    width: 500px;
    height: 700px;
  }

  .post:hover{
    cursor: pointer;
  }

  .postPage{
    max-width: 1080px;
    margin: 0 auto;
    margin-top: 5rem;
  }
</style>

