<template>
  <header
    id="AboutMe"
    class="relative bg-cover bg-center"
    style="
      background-image: url('https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExeHRtaWJqdWsyNTQ2YzBuNTN6YWp5d3M5aHVvMXh2cmhvaHRycmxyeCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/yWQ5pVIzz7nxOgL10o/giphy.webp');
    "
  >
    <div class="absolute inset-0 bg-black/50"></div>


    <div class="relative z-10 mx-auto max-w-7xl px-6 py-16 grid grid-cols-1 md:grid-cols-2 items-center gap-8">
      <div class="max-w-3xl">
        <h1 class="text-4xl md:text-6xl font-serif mb-6 text-white text-shadow-lg">About Me</h1>
        <p class="text-lg md:text-xl font-medium leading-relaxed text-gray-200">
          ผมชื่นชอบและรักการเล่นเกมเป็นอย่างมาก
          มันเป็นจุดเริ่มต้นที่ทำให้ผมได้หันมาสนใจเรื่องการเขียนโปรแกรม ในเป้าหมายที่ผมได้ตั้งเอาไว้
          ผมอยากจะสร้างเกมเป็นของตนเอง อยากมีคอมมูนิตี้ที่ไว้พูดคุยเกี่ยวกับเกมของผม
          ผมจึงมองหาประสบการณ์หรือความรู้ใหม่ๆ ติดตัวเอาไว้
          เพื่อพัฒนาทักษะของตัวเองให้มีความสามารถหลากหลายด้าน
          ในซักวันผมจะได้ยืดอกและภูมิใจที่ผมได้มีเกมที่ผมสร้างเป็นของตนเอง
        </p>
      </div>
      <!--  max-w-sm md:max-w-md hover:scale-105 transition-transform duration-300 -->
      <div class="flex justify-end">
        <img
          src="https://scontent-atl3-2.xx.fbcdn.net/v/t1.15752-9/467471253_3779655088953676_2248807456982720390_n.jpg?stp=dst-jpg_s552x414_tt6&_nc_cat=111&ccb=1-7&_nc_sid=0024fc&_nc_eui2=AeH9nPZ2PdGDhhrj1qXVnVDZ-7CdTdlwFEv7sJ1N2XAUS15fj7WMgr8B3gYhl1kSuCrqjxta6GvUn3_ALnH16KVM&_nc_ohc=Xjtk2nI7l74Q7kNvgHkWeNj&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent-atl3-2.xx&oh=03_Q7cD1gFvpiwk6lSMs6YcHrgf20mHFhKC7hnCv_AMeU7fPpnLhQ&oe=678B4124"
          alt="My Image"
          class="w-full hover:scale-105 h-64 object-cover shadow-lg rounded-lg float-right shadow-md ml-20"
        />
      </div>
      <div class="flex flex-col space-y-4">
        <a :download="Tanwa" :href="cvLink">
        <button class="bg-gray-800/100 w-40 text-white flex justify-center items-center gap-2 shadow-lg shadow-cyan-500/50"> Download CV <img src="https://static.xx.fbcdn.net/images/emoji.php/v9/tb7/1/32/1f4c4.png" alt="CV">
        </button>
      </a>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  data(){
    return{
      cvLink:CV
    }
  }
}
import CV from "../assets/TUNWA CHAIRATTANANON .pdf"
</script>

<style scoped>
header {
  font-family: 'Arial', serif;
}

h1 {
  font-family: 'Poppins', serif;
  font-style: normal;
  font-weight: 400;
  text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.8);
}

h5 {
  font-family: 'Sarabun', serif;
  font-style: normal;
  font-weight: 300;
  text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.6);
  line-height: 1.8;
}

.bg-cover {
  background-size: cover;
}

.bg-center {
  background-position: center;
}

.bg-black\/50 {
  background-color: rgba(0, 0, 0, 0.5);
}
</style>

