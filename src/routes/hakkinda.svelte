<script context="module">
    export const prerender = true;
</script>

<style lang="scss">
    * {
        font-family: sans-serif;
    }

    .information {
        display: flex;
        flex-direction: column;
        margin-left: 1.25em;

        & > * {
            width: 100%;
        }
    }

    .license {
        max-width: 50em;
        margin: 2.5em 0 0 5em;
    }

</style>

<main class="page-segment">
    <h1>Taktisyen Hakkında</h1>

    <div class="information">
        <div><a href="https://github.com/EmreOzcan/taktisyen">Kaynak Kodu</a></div>
        <div>&copy; 2020, 2021 Emre Özcan</div>
    </div>

    <p>Taktisyen'in kaynak kodu MIT Lisansı altında dağıtılmaktadır</p>

    <div class="license">
        <h2>MIT License</h2>

        <p>Copyright (c) 2020, 2021 Emre Özcan</p>

        <p>
            Permission is hereby granted, free of charge, to any person obtaining a copy
            of this software and associated documentation files (the "Software"), to deal
            in the Software without restriction, including without limitation the rights
            to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
            copies of the Software, and to permit persons to whom the Software is
            furnished to do so, subject to the following conditions:
        </p>

        <p>
            The above copyright notice and this permission notice shall be included in all
            copies or substantial portions of the Software.
        </p>

        <p>
            THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
            IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
            FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
            AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
            LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
            OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
            SOFTWARE.
        </p>
    </div>
</main>
