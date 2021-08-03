<script>
    let photoKegiatan1 = './img/photoKegiatan1.jpg'
    let photoKegiatan2 = './img/photoKegiatan2.jpg'
    let photoKegiatan3 = './img/photoKegiatan3.jpg'
    let LogoBerbagi = './img/LogoBerbagi.jpg'
</script>

<div id="badan">
    <!--Deskripsi BTAR-->
    <img src={LogoBerbagi} alt='LogoBerbagi' id="logo">
    <div id="BTAR">
        <p>BERBAGI TAK AKAN RUGI</p>
    </div>
    <div id="deskripsiBTAR">
        <p>
            <span>Lorem ipsum dolor sit amet, consectetur adipiscing</span><br/> 
            <span>elit, sed do eiusmod tempor incididunt ut </span><br/>
            <span> labore et dolore magna aliqua.</span>
        </p>
    </div>

    <!--Gambar Kegiatan-->
    <div id="textKegiatan">
        <p>KEGIATAN</p>
    </div>
    <div id="Kegiatan">
        <div class="Card">
            <img src={photoKegiatan1} alt="photoKegiatan1">
                <div class="Content-Card">
                    <p>Judul</p>
                    <p>lorem ipsum dolor sit amet, constructor adpiscing</p>
                </div>
        </div>
        <div class="Card">
            <img src={photoKegiatan2} alt="photoKegiatan1">
                <div class="Content-Card">
                    <p>Judul</p>
                    <p>lorem ipsum dolor sit amet, constructor adpiscing</p>
                </div>
        </div>
        <div class="Card">
            <img src={photoKegiatan3} alt="photoKegiatan1">
                <div class="Content-Card">
                    <p>Judul</p>
                    <p>lorem ipsum dolor sit amet, constructor adpiscing</p>
                </div>
        </div>
    </div>

    <!-- Bagian Jumlah Donasi-->
    <div id="Donasi">
        <div class="custom-shape-divider-top-1628004816">
            <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
                <path d="M649.97 0L550.03 0 599.91 54.12 649.97 0z" class="shape-fill"></path>
            </svg>
        </div>
        <p>TOTAL DONASI</p>
        <p>RP 44.500.678</p>
    </div>
    <div class="custom-shape-divider-top-1628005740">
        <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
            <path d="M649.97 0L550.03 0 599.91 54.12 649.97 0z" class="shape-fill"></path>
        </svg>
    </div>
</div>



<style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
    #badan{
        height:200px;
        text-align: center;
    }
    #logo{
        border:20px;
        background-color: #FFB4B4;
        width:200px;
        height:200px;
        border-radius: 100px;
        text-align: center;
        align-items: center;
        margin-top: 5%;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    }

    #BTAR{
    font-family: 'Roboto';
    font-style: normal;
    font-weight: normal;
    font-size: 2em;
    line-height: 14px;
    color: #414141;
    }
    #deskripsiBTAR{
    font-family: 'Roboto';
    font-style: normal;
    font-weight: normal;
    font-size: 1.5em;
    line-height: 25px;
    color: #414141;
    gap: 5px;
    }

    #textKegiatan{
    margin-top: 10%;
    font-family: 'Roboto';
    font-style: normal;
    font-weight: normal;
    font-size: 2em;
    line-height: 14px;
    color: #414141;
    }

    #Kegiatan{
        margin-left: 20px;
        display: inline-flex;
        gap: 20px;
    }

    .Card{
        max-width: 250px;
        border-radius: 10px;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    }

    .Card img{
        width:250px ;
        border-radius: inherit;
    }

    #Donasi{
        margin-top: 5%;
        height: 400px;
        background-color: #FFDCDC;
        line-height: 10px;
    }

    .custom-shape-divider-top-1628004816 {
    top: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    }

    .custom-shape-divider-top-1628004816 svg {
        display: block;
        width: calc(100% + 1.3px);
        height: 103px;
    }

    .custom-shape-divider-top-1628004816 .shape-fill {
        fill: #FFFBFB;
    }

    #Donasi p:nth-child(2){
        font-size: 40px;
        color: #414141;
        font-family: 'Roboto';
    }

    #Donasi p:nth-child(3){
        font-size: 100px;
        color: #414141;
        font-family: 'Roboto';
        margin-bottom: 2%;
    }

    .custom-shape-divider-top-1628005740 {
    top: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    }

    .custom-shape-divider-top-1628005740 svg {
        width: calc(100% + 1.3px);
        height: 103px;
    }

    .custom-shape-divider-top-1628005740 .shape-fill {
        fill: #FFDCDC;
    }

</style>