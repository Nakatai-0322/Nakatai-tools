<template>
    <div class="hello">
        <h1>{{ msg }}</h1>
        <p>
            Nakataiが作成したツールの紹介です。
        </p>
        <h3>乱数生成器</h3>
        <ul>
            確かJavaScriptではじめて作ったツールです。<br>
            Chance.jsというライブラリを使用しました。<br>
            <a href="https://rannum.nakatai.ga">使ってみる</a><br>
            <a href="https://github.com/Nakatai-0322/Check-Kun">ソースコード</a>
        </ul>
        <h3>アクセス環境表示ツール</h3>
        <ul>
            IPアドレスなどを表示できます。<br>
            <a href="https://check.nakatai.ga">使ってみる</a><br>
            <a href="https://github.com/Nakatai-0322/Check-Kun">ソースコード</a>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'HelloWorld',
    props: {
        msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
    margin: 40px 0 0;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    display: inline-block;
    margin: 0 10px;
}

a {
    color: #42b983;
}
</style>
