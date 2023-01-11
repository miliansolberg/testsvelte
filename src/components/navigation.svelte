<script>

</script>
<main>

    <ul>
        <img class="logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Svelte_Logo.svg/498px-Svelte_Logo.svg.png?20191219133350" alt="sveltelogo">
        <li><a href='/'>App</a></li>
        <li><a href='/'>Protocol</a></li>
        <li><a href='/'>Software</a></li>
    </ul>
</main>

<style>

    a {
        color: #fff;
        text-decoration: none;
    }

    ul {
        margin: 30px 785px;
    }

    ul li {
        font-size: 1.1rem;
        display: inline-block;
        margin: 0px 25px;
    }

    a:hover {
        opacity: 0.8;
    }

    .logo {
        position: absolute;
        left: 425px;
        top: 15px;
        height: 55px;
        width: 46px;

    }

    @media only screen and (max-width: 768px) {
        .logo {
          height: 45px;
          width: 37.5px;
        }
      }

      @media only screen and (max-width: 675px) {
        ul li {
            display: block;
            text-align: center;
        }
      }

</style>