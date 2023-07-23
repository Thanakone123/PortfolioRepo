<template>
    <div>
        <div class="d-flex justify-content-center mb-3 p-5 pb-2" style="min-height: 250px;">
            <img width="200" height="200" class="rounded-2 shadow-lg" src="/images/un.jpg" alt="thanakone">
        </div>
        <div class="d-flex justify-content-center">
            <div class="text-center">
                <p>Hello, I am a programmer named</p>
                <div class="fw-bold typewriter"><span class="color-red">T</span>hanakone <span
                        class="color-red">H</span>EUENNAVONGSA</div>
            </div>
        </div>
    </div>
    <div style="height: 100000px;"></div>
    <div class="text-center mt-5">
        <img src="../../assets/icons/mafu-mafumafu.gif" width="70" height="70">
        <p>Sorry for wasting your time, bro.</p>
    </div>
</template>

<style scoped>
.color-red {
    color: rgb(255, 0, 0);
}

.typewriter {
    color: #000000;
    overflow: hidden;
    /* Ensures the content is not revealed until the animation */
    border-right: .15em solid orange;
    /* The typewriter cursor */
    white-space: nowrap;
    /* Keeps the content on a single line */
    margin: 0 auto;
    /* Gives that scrolling effect as the typing happens */
    letter-spacing: .15em;
    /* Adjust as needed */
    animation:
        typing 3.5s steps(30, end),
        blink-caret .5s step-end infinite;
    word-wrap: break-word;
    /* Allow text to wrap onto new line */
}

/* The typing effect */
@keyframes typing {
    from {
        width: 0
    }

    to {
        width: 100%
    }
}

/* The typewriter cursor effect */
@keyframes blink-caret {

    from,
    to {
        border-color: transparent
    }

    50% {
        border-color: rgb(255, 0, 0)
    }
}
</style>
