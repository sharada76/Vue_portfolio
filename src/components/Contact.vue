<template>
    <div>
        <h1 class="content-title"><font-awesome-icon icon="handshake" class="icon"/> Contact</h1>
        <div class="sam">
            <div class="link">
                <a href="mailto:shin.ex1216@gmail.com" class="link-icon"><font-awesome-icon icon="envelope" class="web-icon mail"/></a>
                <a href="http://github.com/sharada76" class="link-icon"><font-awesome-icon :icon="['fab','github']" class="web-icon github"/></a>
            </div>
        </div>
    </div>
</template>

<style>

.sam{
    text-align: center;
}
.link{
    display:inline-flex;
    width: 30%;
    justify-content: center;
}

.link-icon{
    margin: 0 10px;
    margin-bottom: 20px;
}

.web-icon{
    font-size: 2em;
    background-color: white;
    padding:0.3em;
    border-radius: 50%;
}

.web-icon:hover{
    color: white;
}

.twitter{
    color: #1DA1F2;
}
.twitter:hover{
    background-color: #1DA1F2;
}


.mail{
    color: #DD5144;
}
.mail:hover{
    background-color: #DD5144;
}

.github{
    color: #171515;
}
.github:hover{
    background-color: #171515;
}

.hateblo{
    color: #193278;
}
.hateblo:hover{
    background-color: #193278;
}

@media screen and (max-width: 768px){
    .web-icon{
        color:white;
    }

    .twitter{
        background-color: #1DA1F2;
    }

    .mail{
        background-color: #DD5144;
    }

    .github{
        background-color: #171515;
    }

    .hateblo{
        background-color: #193278;
    }
}
</style>

