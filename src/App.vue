
<template>
    <header class="header">
        <i class='bx bx-menu' id="menu-icon"></i>
        <a href="#" class="logo">Portfolio</a>

        <nav class="navbar">
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skil">Skil</a>
            <a href="#portofolio">Portofolio</a>
            
        </nav>
    </header>
    
    <section class="home" id="home">
        <div class="home-content">
            <h3>halo, its me</h3>
            <h1>Haikal Rahman</h1>
            <h3>and i'm a <span>Frontend Developer</span></h3>
            <p>"Selamat datang di profil pribadi saya! Sebagai mahasiswa Teknik Informatika 
                dengan gairah yang mendalam terhadap pengembangan web dan perangkat lunak, 
                saya berbagi cerita hidup, pemikiran, dan inspirasi di sini. Melalui perjalanan hidup saya, 
                saya berharap dapat memberikan inspirasi dan bantuan kepada Anda dalam menjalani perjalanan Anda sendiri. 
                Terima kasih telah singgah, dan mari kita bersama-sama menjelajahi dan meraih mimpi-mimpi kita!"</p>
            <div class="social-media">
                <a href="#"><i class='bx bxl-facebook'></i></a>
                <a href="#"><i class='bx bxl-twitter'></i></a>
                <a href="#"><i class='bx bxl-instagram' ></i></a>
                <a href="#"><i class='bx bxl-youtube' ></i></a>
            </div>
            <ButtonVue buttonName="Download CV"></ButtonVue>
        </div>

        <div class="home-img">
            <img src="./assets/img/gambar.jpg" alt="" >
        </div>
        
        
    </section>

    <section class="about" id="about">
        <div class="about-img">
            <img src="./assets/img/gambar basket.jpg" alt="hobi" >
        </div>
        

        <div class="about-content">
            <h2 class="heading">About <span>Me</span></h2>
            <h3>Frontend Developer</h3>
            <p>Nama : M. Haiqal Rahman</p>
            <p>Tempat/Tanggal Lahir : Pekanbaru, 19 juni 2004</p>
            <p>Jurusan : Teknik Informatika</p>
            <p>Hobi : Olahraga Basket</p>
                <a href="#"><ButtonVue  buttonName="Read More"></ButtonVue></a>
        </div>
    </section>

    <section class="skil" id="skil">
        <h2 class="heading">Skil <span>Kemampuan</span></h2>

        <div class="skil-container">
            <div class="skil-box">
                <i class='bx bx-code-alt'></i>
                <h1>Web Development</h1>
                
                <ButtonVue buttonName="Read More"></ButtonVue>
            </div>
            
            <div class="skil-box">
                <i class='bx bx-palette' ></i>
                <h1>Graphic Design</h1>
                
                <ButtonVue buttonName="Read More"></ButtonVue>
            </div>

            <div class="skil-box">
                <i class='bx bxs-camera' ></i>
                <h1>Fotografer</h1>
                
                <ButtonVue buttonName="Read More"></ButtonVue>
            </div>
        </div>
    </section>

    <section class="portofolio" id="portofolio">
        <h2 class="heading">Latest <span>Project</span></h2>

        <div class="project-img">
            <a href=""><img src="./assets/img/sampul.png" alt=""></a>
            <a href=""><img src="./assets/img/halaman1.jpg" alt=""></a>
            <a href=""><img src="./assets/img/halaman2.jpg" alt=""></a>
            <a href=""><img src="./assets/img/halaman3.png" alt=""></a>
        </div>
        <p>Ini adalah project yang saya kerjakan bersama tim saya dan kami menamai nya dangan SiDarling, 
        peoject ini bertujuan untuk mempermuadah para masyarakat untuk membuang sampah untuk mendapatkan uang.
        aplikasi ini membantu untuk tidak tercemarnya lingkungan. Daur ulang dapat menjadi sumber potensial pendapatan. 
        Aplikasi yang memfasilitasi proses daur ulang dapat menghubungkan antara pihak yang memiliki barang daur ulang 
        dengan pihak yang membutuhkannya, menciptakan peluang bisnis yang menguntungkan.
        Membangun aplikasi daur ulang juga merupakan peluang untuk mengembangkan inovasi teknologi yang dapat meningkatkan 
        efisiensi dan efektivitas dalam pengelolaan limbah. Ini dapat mencakup penggunaan sensor cerdas, kecerdasan buatan, 
        dan teknologi lainnya untuk mengoptimalkan proses daur ulang.
        </p>
    </section>
    
    
    <footer>
        <p> &copy; M. Haiqal Rahman - Teknik Informatika </p>
        <ButtonVue></ButtonVue>
    </footer>
</template>

<script>
import ButtonVue from './components/Button.vue'
import SosmedVue from './components/icon.vue'

export default{
    name:app,
    components:{
        ButtonVue
    }
}

</script>

