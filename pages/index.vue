<template>
    <div>
        <h1>Home Page</h1>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Vero, ut laborum ipsa pariatur dicta saepe impedit soluta sed, hic voluptas modi nemo ducimus odio tenetur, laudantium velit qui numquam magni.</p>

        <div class="sambutan flex justify-center items-center m-20">
            <div class="relative w-[1180px] h-[392px] rounded-[12px] overflow-hidden bg-[url(https://2.bp.blogspot.com/-EHQhGRau2Aw/VzLTtiji06I/AAAAAAAAARg/MvH26rSCuNo0Gnz-miJfW2e-iMhIqOJxgCLcB/s1600/kampus.jpg)] bg-cover bg-[50%_50%]">
                <div class="absolute top-0 left-0 w-full h-full bg-white opacity-90"></div>
                <div class="inline-flex flex-col items-start gap-[15px] absolute top-[37px] left-[381px]">
                    <div class="relative w-fit mt-[-1.00px] font-extrabold text-[#063556] text-[36px] tracking-[0] leading-[normal]">
                        SAMBUTAN DEKAN
                    </div>
                    <div class="flex flex-col w-[759px] items-start gap-[4px]">
                        <p class="relative self-stretch font-normal text-[#353535] text-[14px] tracking-[0] leading-[normal]">
                        <span class="font-normal text-[#353535] text-[14px] tracking-[0]">
                            Assalamualaikum Warahmatullahi Wabarakatuh
                            <br />
                        </span>
                        </p>
                        <p class="relative self-stretch font-normal text-[#353535] text-[14px] tracking-[0] leading-[normal]">
                        <span class="font-normal text-[#353535] text-[14px] tracking-[0]">
                            Puji syukur kehadirat Tuhan Yang Maha Kuasa atas limpahan rahmat dan hidayah-Nya sehingga informasi
                            tentang Fakultas Teknik Unhas melalui situs web ini dapat terwujud. Besar harapan kita semoga ridho-Nya
                            menyertai segala aktifitas dalam upaya pembinaan sumber daya manusia dalam bidang teknologi dan semoga
                            informasi melalui web ini dapat berguna bagi semua pihak. Kami dari semua civitas akademika Fakultas
                            Teknik dengan semua dukungan komponen perguruan tinggi yang ada akan terus meningkatkan pencapaian menuju
                            terwujudnya visi dan misi yang telah dicanangkan dalam rencana strategis fakultas. Semoga informasi yang
                            diberikan lewat layanan website ini dapat memberikan gambaran situasi dan kondisi Fakultas Teknik kepada
                            semua lapisan masyarakat. Selamat Datang di Fakultas Teknik Universitas Hasanuddin.
                        </span>
                        </p>
                    </div>
                    <p class="relative w-fit font-bold text-[#063556] text-[14px] text-center tracking-[0] leading-[normal]">
                        Prof. Dr. Eng. Muhammad Isran Ramli, ST., MT
                    </p>
                </div>
                <img class="absolute w-[332px] h-[392px] top-0 left-0" alt="Dr eng ir muhammad" src="../assets/foto dekan.png"
                />
            </div>
        </div>

        <div class="pengumuman m-20">
            <TextTitle textTitle="PENGUMUMAN" />
            
            <div class="isi-pengumuman m-10 flex justify-center flex-wrap">
                <PengumumanCard className="dies" title="Dies Natalis FT-UH" date="26/09/2021" />
                <PengumumanCard className="bangkit" title="Bangkit Academy 2022" date="26/09/2021"/>
                <PengumumanCard className="seminar" title="Seminar Proposal" date="26/09/2021"/>
            </div>
        </div>

        <div class="berita m-20">
            <TextTitle textTitle="BERITA" />
            <div class="isi-berita flex justify-center flex-wrap">
                <div class="berita-1 m-5">
                    <img class="mt-[45px] mb-[13px]" src="../assets/berita1.png" alt="">
                    <BeritaCard judul="Dies Natalies FT-UH" date="26/09/2023"/>
                </div>
                <div class="berita-2 m-5">
                    <img class="mt-[45px] mb-[13px]" src="../assets/berita2.png" alt="">
                    <BeritaCard judul="Gaji dinaikkan 5% Dosen Senang" date="26/09/2023"/>
                </div>
                <div class="berita-3 m-5">
                    <img class="mt-[45px] mb-[13px]" src="../assets/berita3.png" alt="">
                    <BeritaCard judul="Hoax: Penurunan UKT" date="26/09/2023"/>
                </div>
                <div class="berita-4 m-5">
                    <img class="mt-[45px] mb-[13px]" src="../assets/berita4.png" alt="">
                    <BeritaCard judul="Urgensi Gender di FT-UH" date="26/09/2023"/>
                </div>
                <div class="berita-5 m-5">
                    <img class="mt-[45px] mb-[13px]" src="../assets/berita5.png" alt="">
                    <BeritaCard judul="Kunjungan Kerja Tim FT" date="26/09/2023"/>
                </div>
                <div class="berita-6 m-5">
                    <img class="mt-[45px] mb-[13px]" src="../assets/berita6.png" alt="">
                    <BeritaCard judul="Kalla Kampus Talk 2022" date="26/09/2023"/>
                </div>
            </div>
        </div>

        <div class="peta-kampus m-20">
            <TextTitle textTitle="PETA KAMPUS"/>
            <div class="maps flex justify-center m-10">
                <iframe class="w-[1180px] " src="https://unhas.ac.id/petakampus/virtualtour/index.php?scene=outdoortheater" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
       
    }
</script>

<style scoped>

</style>