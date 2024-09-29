<script setup>
import { CheckCircleIcon } from '@heroicons/vue/24/solid'
</script>

<template>
    <header
        class="sticky top-0 z-20 bg-white border-b p-3 flex justify-between items-center"
    >
        <a href="#">
            <img src="./assets/logo.png" alt="logo" class="h-9" />
        </a>

        <a href="#" class="text-sm">
            <div v-if="true" class="flex items-center gap-1">
                Day complete!
                <CheckCircleIcon class="h-7 text-green-500" />
            </div>
            <div v-else class="flex items-center gap-1">
                Progress: <span class="font-mono">20 %</span>
                <div class="w-3 h-3 rounded-full bg-red-500"></div>
            </div>
        </a>
    </header>
    <main>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laudantium
        magnam nisi numquam ratione sit ut vitae voluptate. Cum dolor earum
        expedita impedit iure nemo perspiciatis ullam? Accusamus amet animi
        beatae dolore doloribus eaque maxime nihil sequi totam velit? Cupiditate
        deleniti deserunt doloremque eius enim error eveniet in laborum magni,
        modi mollitia natus neque nostrum odit perspiciatis quos sed sint
        voluptate? Accusantium beatae cupiditate dignissimos distinctio ea
        eligendi et excepturi ipsa, ipsum non nulla provident quidem repellendus
        voluptates voluptatum? Accusantium asperiores dolores eveniet labore
        maxime modi numquam? Adipisci aliquid asperiores aut autem debitis
        dicta, doloribus facere, in natus nesciunt nostrum officia perspiciatis
        quas quidem quod repellendus vel! Debitis, deleniti dicta facere
        facilis, in, ipsa laudantium mollitia recusandae rerum saepe temporibus
        unde voluptatem? Assumenda commodi consequuntur deserunt doloremque
        ducimus ex facere fugiat fugit, magnam minus molestiae natus nihil,
        officiis optio reprehenderit rerum voluptas voluptates. Eveniet fugit
        molestiae neque nobis numquam optio perspiciatis repudiandae voluptate
        voluptates! Ex laboriosam nobis obcaecati quae sequi? Ab alias aliquam
        aliquid aspernatur consectetur corporis cumque cupiditate delectus dicta
        dolore doloremque eaque eius eligendi ex expedita impedit ipsam itaque,
        necessitatibus nisi nostrum obcaecati odio officiis optio pariatur
        perferendis porro possimus quae quos ratione rem rerum saepe sed sequi
        temporibus vel voluptates, voluptatibus. Cum dignissimos esse eum,
        eveniet, illo minima modi necessitatibus nulla officia repellendus rerum
        saepe vitae voluptatum! Eius expedita in veritatis? Ab animi cupiditate
        eos error fugiat quis reprehenderit. Dolor enim fuga ipsum labore
        molestiae optio perferendis possimus quas sequi, similique sit, soluta.
        Asperiores atque consectetur delectus dignissimos doloribus facilis,
        fugiat nesciunt odio quas quasi ullam vitae voluptate voluptatum. Ab,
        accusantium aliquid delectus, deleniti dignissimos dolorem eaque eveniet
        explicabo inventore, ipsa magnam natus praesentium quae qui sunt vitae
        voluptatibus. Aliquam ducimus fugit harum nam nostrum ratione tenetur
        veritatis voluptatem? Accusamus ad aliquam assumenda consequatur
        corporis deleniti dignissimos dolor, dolore ea eius eligendi et facere
        facilis hic incidunt ipsum iste magni non obcaecati odit officiis omnis,
        placeat praesentium, quas recusandae repellat repudiandae similique
        tempora tenetur velit. Asperiores blanditiis consectetur debitis earum,
        eius eos iusto optio quaerat quos tenetur, veniam, vero voluptates.
        Adipisci culpa cum fugiat neque quod! Amet asperiores culpa dolor
        dolores eligendi eos error ex excepturi, expedita facere id, itaque
        magni maiores molestiae neque nihil odio optio quis quos vitae?
        Aspernatur facilis fuga fugit id illo laboriosam minima, modi
        praesentium sapiente unde. Aliquam animi aut autem, excepturi natus
        sapiente voluptatum. Asperiores culpa debitis dicta id tempora. Aliquam
        consequuntur cum, cupiditate deleniti doloribus eius error
        exercitationem facere hic incidunt minima nihil obcaecati odit omnis
        quaerat quo reprehenderit. Alias amet aspernatur blanditiis dolor eos
        esse fugiat magni natus officia pariatur, perspiciatis quaerat similique
        vitae? Accusamus architecto minus sapiente ut voluptatibus? Est et
        exercitationem illo inventore officiis perspiciatis praesentium
        voluptas? A amet assumenda atque aut beatae consequuntur fuga iure
        laborum molestias, mollitia neque nisi nobis obcaecati perferendis
        repellendus saepe similique sunt tempore tenetur voluptatibus.
        Consectetur quis sapiente totam veritatis. Ab debitis delectus dolor
        enim eos esse est eum fuga inventore laudantium obcaecati porro possimus
        quae sequi tempora vel veniam, veritatis voluptatum!
    </main>
    <nav>NAV</nav>
</template>
