<template>
    <my-page title="超级拓展" :page="page">
        <ui-article>
            <p>超级拓展是一个功能强大的浏览器拓展，她致力于让浏览器的功能更加强大，帮助我们更好地提高效率。</p>

            <h2>软件特色</h2>
            <ul>
                <li>Material Design 风格 UI，界面简洁美观。</li>
                <li>功能强大，内置多个小功能，一个插件解决常见的大部分需求。</li>
                <li>设置项丰富，支持多种个性化设置。</li>
            </ul>

            <h2>功能</h2>
            <ul>
                <li>支持搜索框，可配置多种搜索引擎。</li>
                <li>支持网页二维码。</li>
                <li>支持设置网页背景色。</li>
                <li>支持简单的待办事项。</li>
                <li>支持图片右键菜单直接下载图片，不用弹出对话框。</li>
                <li>内置应用商店，可以快速添加优质应用。</li>
            </ul>

            <h2>截图</h2>
            <p><img src="/static/img/screenshot/1.png"></p>

            <h2>下载</h2>
            <ui-raised-button primary label="Chrome 应用商店下载" href="https://chrome.google.com/webstore/detail/ejfhencngpnpohkchdjgkphiakibkkab" target="_blank" />
        </ui-article>
    </my-page>
</template>

<script>
    export default {
        data () {
            return {
                page: {
                    menu: [
                        {
                            type: 'icon',
                            icon: 'apps',
                            href: 'https://app.yunser.com/',
                            target: '_blank',
                            title: '应用'
                        }
                    ]
                }
            }
        }
    }
</script>

<style scoped>
img {
    max-width: 600px;
}
</style>
