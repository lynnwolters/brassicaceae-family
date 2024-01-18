<header>
    <ul class="header-left">
        <li>
            <a href="#">
                <div>
                    <div>
                        <img src="images/tree.svg" alt="tree">
                    </div>
                    <div>
                        <p>Tree Of Life</p>
                    </div>
                </div>
                <div>
                    <p>Brassicaceae</p>
                </div>
            </a>
        </li>
        <li>
            <form>
                <input type="text" placeholder="Search...">
                <button>
                    <div>
                        <img src="images/search.svg" alt="search">
                    </div>
                </button>
            </form>
        </li>
    </ul>
    <ul class="header-right">
        <li>
            <button>
                <div>
                    <img src="images/relation.svg" alt="relation">
                </div>
                <div>
                    <p>Relation</p>
                </div>
            </button>
        </li>
        <li>
            <button>
                <div>
                    <img src="images/filter.svg" alt="filter">
                </div>
                <div>
                    <p>Filter</p>
                </div>
            </button>
        </li>
    </ul>
</header>

<main>
    <section></section>
</main>

<footer>
    <ul class="footer-right">
        <li>
            <button>
                <div>
                    <img src="images/zoom-in.svg" alt="zoom-in">
                </div>
            </button>
        </li>
        <li>
            <button>
                <div>
                    <img src="images/zoom-out.svg" alt="zoom-out">
                </div>
            </button>
        </li>
    </ul>
</footer>

<style>
    /* ******* */
    /* HEADER */
    /* ****** */

    header {
        height: 8em;

        display: flex;
        justify-content: space-between;

        padding: 1em 1em 0 1em;

        background-color: transparent;
    }

    .header-left {
        height: 5em;
    }

    .header-left li {
        list-style: none;
    }

    .header-left li:nth-of-type(1) a {
        height: 2.5em;

        display: flex;
        align-items: center;

        margin-bottom: 1em;

        color: var(--color-1);
        text-decoration: none;
    }

    .header-left li:nth-of-type(1) a > div {
        height: 100%;

        padding: 0 1em;
    }

    .header-left li:nth-of-type(1) a > div:nth-of-type(1) {
        display: flex;
        align-items: center;

        border-radius: 6em 0 0 6em;

        background-color: var(--color-4);
    }

    .header-left li:nth-of-type(1) a > div:nth-of-type(1) div:nth-of-type(1) {
        width: fit-content;
        height: 100%;

        display: flex;
        justify-content: start;
        align-items: center;
    }

    .header-left li:nth-of-type(1) a > div:nth-of-type(1) div:nth-of-type(1) img {
        width: 50%;
    }

    .header-left li:nth-of-type(1) a > div:nth-of-type(1) div:nth-of-type(2) p {
        font-weight: bold;
    }

    .header-left li:nth-of-type(1) a > div:nth-of-type(2) {
        display: flex;
        justify-content: end;
        align-items: center;

        border-radius: 0 6em 6em 0;

        background-color: var(--color-3);
    }

    .header-left li:nth-of-type(2) form {
        height: 2.5em;

        display: flex;
        align-items: center;
    }

    .header-left li:nth-of-type(2) form input {
        width: 100%;
        height: 100%;

        padding: 0 1em;

        border: solid .1em var(--color-3);
        border-radius: 6em 0 0 6em;

        background-color: var(--color-1);

        color: var(--color-3)
    }

    .header-left li:nth-of-type(2) form input::placeholder {
        color: var(--color-3)
    }

    .header-left li:nth-of-type(2) form input:focus {
        outline: none;
    }

    .header-left li:nth-of-type(2) form button {
        aspect-ratio: 1/1;
        height: 100%;

        display: flex;
        justify-content: center;

        border: none;
        border-radius: 0 6em 6em 0;

        background-color: var(--color-3);
    }

    .header-left li:nth-of-type(2) form button div {
        height: 100%;

        display: flex;
        justify-content: center;
        align-items: center;
    }

    .header-left li:nth-of-type(2) form button div img {
        width: 50%;
    }

    .header-left li:nth-of-type(2) form button:hover {
        background-color: var(--color-4);
    }

    .header-right {
        height: 2.5em;

        display: flex;
    }

    .header-right li {
        list-style: none;
    }

    .header-right li button {
        height: 100%;

        display: flex;
        align-items: center;

        padding: 0 1em;

        border: none;
        border-radius: 6em;

        background-color: var(--color-3);
        color: var(--color-1)
    }

    .header-right li button div:nth-of-type(1) {
        width: fit-content;
        height: 100%;

        display: flex;
        justify-content: start;
        align-items: center;
    }

    .header-right li button div:nth-of-type(1) img {
        width: 50%;
    }

    .header-right li button div:nth-of-type(2) {
        width: fit-content;
        height: 100%;

        display: flex;
        justify-content: end;
        align-items: center;
    }

    .header-right li:nth-of-type(1) button:nth-of-type(1) {
        margin-right: 1em;
    }

    .header-right li button:hover {
        background-color: var(--color-4);
    }

    /* **** */
    /* TOL */
    /* *** */

    main > section {
        height: calc(100vh - 16em);
    }

    /* ******** */
    /* FOOTER */
    /* ******* */

    footer {
        height: 8em;

        display: flex;
        justify-content: end;
        align-items: center;

        padding: 0 1em 1em 1em;

        background-color: transparent;
    }

    .footer-right {
        height: 5em;

        list-style: none;
    }

    .footer-right li {
        height: 2.5em;
    }

    .footer-right li button {
        height: 100%;

        padding: 0 1.5em;

        border: none;
        border-radius: 6em;

        background-color: var(--color-3);
        color: var(--color-1)
    }

    .footer-right li button div {
        width: fit-content;
        height: 100%;

        display: flex;
        align-items: center;
        justify-content: center;
    }

    .footer-right li button div img {
        width: 50%;
    }

    .footer-right li:nth-of-type(1) {
        margin-bottom: 1em;
    }

    .footer-right li button:hover {
        background-color: var(--color-4);
    }
</style>