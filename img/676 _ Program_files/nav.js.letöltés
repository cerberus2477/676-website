//nav toggle and color change on scroll

const nav = document.querySelector(".main-nav");
const navHeight = nav.getBoundingClientRect().height;

const toggleNav = () => {
    if (nav.dataset.state == "closed") {
        nav.dataset.state = "open";
    } else {
        nav.dataset.state = "closed";
    }
}

window.onscroll = function () {
    if (window.scrollY > navHeight) {
        nav.dataset.scrolled = "true";
    } else {
        nav.dataset.scrolled = "false";
    }
}