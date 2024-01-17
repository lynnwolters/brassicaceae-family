<header>
    <ul>
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
    <ul>
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

<footer></footer>

<style>
    header {
        height: 6em;

        display: flex;
        align-items: center;
        justify-content: space-between;

        background-color: lightgray;
    }

    header > ul:nth-of-type(1) li:nth-of-type(1) a {
        width: fit-content;
        height: 3em;

        display: flex;

        text-decoration: none;
    }

    header > ul:nth-of-type(1) li:nth-of-type(1) a > div:nth-of-type(1) {
        display: flex;
        align-items: center;

        border-radius: 6em 0 0 6em;

        background-color: var(--color-4);

        color: var(--color-1)
    }

    header > ul:nth-of-type(1) li:nth-of-type(1) a > div:nth-of-type(1) > div:nth-of-type(1) {
        width: fit-content;
        height: 100%;

        display: flex;
        justify-content: start;
        align-items: center;

        padding: 0 1em;
    }

    header > ul:nth-of-type(1) li:nth-of-type(1) a > div:nth-of-type(1) > div:nth-of-type(1) img {
        width: 50%;
    }

    header > ul:nth-of-type(1) li:nth-of-type(1) a > div:nth-of-type(2) {
        display: flex;
        align-items: center;

        padding: 0 1em;

        border-radius: 0 6em 6em 0;

        background-color: var(--color-3);

        color: var(--color-1)
    }

    header > ul:nth-of-type(2) {
        display: flex;
    }

    header > ul:nth-of-type(2) li {
        list-style: none;
    }

    header > ul:nth-of-type(2) li button {
        width: fit-content;
        height: 3em;

        padding: 0 1em;

        display: flex;
        align-items: center;

        border: none;
        border-radius: 6em;

        background-color: var(--color-3);

        color: var(--color-1)
    }

    header > ul:nth-of-type(2) li:nth-of-type(1) button {
        margin-right: 1em;
    }

    header > ul:nth-of-type(2) li button div:nth-of-type(1) {
        width: fit-content;
        height: 100%;

        display: flex;
        justify-content: start;
        align-items: center;
    }

    header > ul:nth-of-type(2) li button div:nth-of-type(1) img {
        width: 50%;
    }

    header > ul:nth-of-type(2) li button div:nth-of-type(2) {
        width: fit-content;
        height: 100%;

        display: flex;
        justify-content: end;
        align-items: center;
    }

    header > ul:nth-of-type(2) li button:hover {
        background-color: var(--color-4);
    }

    main > section {
        height: calc(100vh - 12em);
    }

    footer {
        height: 6em;

        background-color: lightgray;
    }
</style>