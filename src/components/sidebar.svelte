<script lang="ts">
    import friends_icon from "../assets/friends_icon.svg";
    import home_icon from "../assets/home-icon.svg";
    import logo from "../assets/logo.png";
    import search_icon from "../assets/search-icon.svg";
    import settings_icon from "../assets/settings-icon.svg";
</script>

<section>
    <img src={logo} alt="/" id="logo" />
    <div class="menu">
        <p>menu</p>
        <div class="menu-component">
            <div class="button-background">
                <img src={home_icon} alt="/" />
            </div>
            <h1>Home</h1>
        </div>
        <div class="menu-component">
            <div class="button-background">
                <img src={friends_icon} alt="/" />
            </div>
            <h1>Friends</h1>
        </div>
        <div class="menu-component">
            <div class="button-background">
                <img src={search_icon} alt="/" />
            </div>
            <h1>Search</h1>
        </div>
        <div class="menu-component">
            <div class="button-background">
                <img src={settings_icon} alt="/" />
            </div>
            <h1>Settings</h1>
        </div>
    </div>
    <div class="playlist">
        <p>playlists</p>
        <div class="playlist-component">
            <div class="playlist-background">
                <img
                    src="https://upload.wikimedia.org/wikipedia/en/e/ed/Green_Day_-_American_Idiot_album_cover.png"
                    alt="/"
                />
            </div>
            <h1>Liked Songs</h1>
        </div>

        <div class="playlist-component">
            <div class="playlist-background">
                <img
                    src="https://upload.wikimedia.org/wikipedia/en/e/ed/Green_Day_-_American_Idiot_album_cover.png"
                    alt="/"
                />
            </div>
            <h1>Vibe Songs</h1>
        </div>

        <div class="playlist-component">
            <div class="playlist-background">
                <img
                    src="https://upload.wikimedia.org/wikipedia/en/e/ed/Green_Day_-_American_Idiot_album_cover.png"
                    alt="/"
                />
            </div>
            <h1>Fan Songs</h1>
        </div>

        <div class="playlist-component">
            <div class="playlist-background">
                <img
                    src="https://upload.wikimedia.org/wikipedia/en/e/ed/Green_Day_-_American_Idiot_album_cover.png"
                    alt="/"
                />
            </div>
            <h1>Lol Songs</h1>
        </div>

        <div class="playlist-component">
            <div class="playlist-background">
                <img
                    src="https://upload.wikimedia.org/wikipedia/en/e/ed/Green_Day_-_American_Idiot_album_cover.png"
                    alt="/"
                />
            </div>
            <h1>Fuck you Songs</h1>
        </div>

        <div class="playlist-component">
            <div class="playlist-background">
                <img
                    src="https://upload.wikimedia.org/wikipedia/en/e/ed/Green_Day_-_American_Idiot_album_cover.png"
                    alt="/"
                />
            </div>
            <h1>Lol</h1>
        </div>

        <div class="playlist-component">
            <div class="playlist-background">
                <img
                    src="https://upload.wikimedia.org/wikipedia/en/e/ed/Green_Day_-_American_Idiot_album_cover.png"
                    alt="/"
                />
            </div>
            <h1>Your mom</h1>
        </div>

        <div class="playlist-component">
            <div class="playlist-background">
                <img
                    src="https://upload.wikimedia.org/wikipedia/en/e/ed/Green_Day_-_American_Idiot_album_cover.png"
                    alt="/"
                />
            </div>
            <h1>Liked Songs</h1>
        </div>

        <div class="playlist-component">
            <div class="playlist-background">
                <img
                    src="https://upload.wikimedia.org/wikipedia/en/e/ed/Green_Day_-_American_Idiot_album_cover.png"
                    alt="/"
                />
            </div>
            <h1>Liked Songs</h1>
        </div>
    </div>
</section>

<style lang="scss">
    @import "../variable.scss";

    section {
        left: 0;
        width: 250px;
        height: 100vh;
        background-color: $background;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 20px 0;
        border-right: 2px solid $secondary;
        position: fixed;
        overflow-y: auto;

        img#logo {
            width: 125px;
            height: 125px;
        }

        .menu {
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 100%;
            height: auto;
            padding: 20px 0;

            p {
                color: $text;
                font-size: 14px;
                margin-bottom: 20px;
                opacity: 0.5;
                font-variant: small-caps;
                text-decoration: underline;
                text-decoration-color: $text;
                text-decoration-thickness: 2px;
                text-underline-offset: 5px;
                user-select: none;
            }

            .menu-component {
                width: 100%;
                height: 50px;
                display: flex;
                flex-direction: row;
                align-items: center;
                margin-bottom: 10px;

                .button-background {
                    width: 45px;
                    height: 45px;
                    margin-left: 20px;
                    border-radius: 15px;
                    background-color: $secondary;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    margin-right: 10px;
                    cursor: pointer;

                    img {
                        width: 65%;
                        height: auto;
                        user-select: none;
                    }
                }

                h1 {
                    color: $text;
                    font-size: 20px;
                    font-weight: 500;
                    margin-left: 5px;
                    user-select: none;
                }
                &:hover {
                    background-color: $secondary;
                    border-radius: 15px;
                    cursor: pointer;
                    width: 80%;
                    transition: 1s;
                }
            }
        }

        .playlist {
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 100%;
            height: auto;
            padding: 20px 0;
            p {
                color: $text;
                font-size: 14px;
                margin-bottom: 20px;
                opacity: 0.5;
                font-variant: small-caps;
                text-decoration: underline;
                text-decoration-color: $text;
                text-decoration-thickness: 2px;
                text-underline-offset: 5px;
                user-select: none;
            }
            .playlist-component {
                width: 100%;
                height: 50px;
                display: flex;
                flex-direction: row;
                align-items: center;
                margin-bottom: 10px;

                .playlist-background {
                    width: 45px;
                    height: 45px;
                    margin-left: 20px;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    margin-right: 10px;
                    cursor: pointer;

                    img {
                        width: 100%;
                        border-radius: 15px;
                        height: auto;
                        user-select: none;
                        filter: grayscale(100%);
                    }
                }

                h1 {
                    color: $text;
                    font-size: 20px;
                    font-weight: 500;
                    margin-left: 5px;
                    user-select: none;
                }
                &:hover {
                    .playlist-background {
                        left: 0;
                        border-radius: 15px;
                        img {
                            filter: grayscale(0%);
                            transition: 0.5s;
                        }
                    }
                    h1 {
                        transition: 0.5s;
                    }
                    cursor: pointer;
                    width: 80%;
                    background-color: $secondary;
                    border-radius: 15px;
                    transition: 1s;
                }
            }
        }
    }
</style>
