<template>
    <Header></Header>
    <nav id="menubar">
        <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="#">COMPANY</a></li>
            <li><a href="#">SERVICE</a></li>
            <li><a href="#">CONTACT</a></li>
            <li><a href="#">CONTACT</a></li>
        </ul>
    </nav>
    <div class="mainimg">
        <div><img src="../assets/images/1.jpg" alt="" ></div>
        <div><img src="../assets/images/2.jpg" alt="" ></div>
        <div><img src="../assets/images/3.jpg" alt="" ></div>
    </div>
    <main>
        <section>
            <h2>お知らせ</h2>
            <dl id="new">
                <dt>2021/12/11</dt>
                <dd>tp_beginner7配布開始。</dd>
                <dt>20XX/00/00</dt>
                <dd>サンプルテキスト。サンプルテキスト。サンプルテキスト。</dd>
                <dt>20XX/00/00</dt>
                <dd>サンプルテキスト。サンプルテキスト。サンプルテキスト。</dd>
                <dt>20XX/00/00</dt>
                <dd>サンプルテキスト。サンプルテキスト。サンプルテキスト。</dd>
                <dt>20XX/00/00</dt>
                <dd>サンプルテキスト。サンプルテキスト。サンプルテキスト。サンプルテキスト。サンプルテキスト。サンプルテキスト。サンプルテキスト。サンプルテキスト。サンプルテキスト。サンプルテキスト。サンプルテキスト。サンプルテキスト。
                </dd>
            </dl>
        </section>
    </main>
    <footer>
        <ul class="icon">
            <li><a href="#"><img src="../assets/images/icon_facebook.png" alt="Facebook"></a></li>
            <li><a href="#"><img src="../assets/images/icon_twitter.png" alt="Twitter"></a></li>
            <li><a href="#"><img src="../assets/images/icon_instagram.png" alt="Instagram"></a></li>
            <li><a href="#"><img src="../assets/images/icon_youtube.png" alt="YouTube"></a></li>
            <li><a href="#"><img src="../assets/images/icon_line.png" alt="LINE"></a></li>
        </ul>
        <small>Copyright&copy; <a href="#">Sample Company</a> All Rights Reserved.</small>
    </footer>
</template>
  
<script lang="ts">
import { defineComponent } from 'vue'
import Header from "./components/Header.vue";

export default defineComponent({
    components: {
        Header
    }
})
</script>
