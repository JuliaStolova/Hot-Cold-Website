<script>
    let lineCount = 4;
    let lineGap = 5;
    let lineHeight = 20;

    let flexAllignCenter = "flex flex-col items-center justify-center w-40 h-40";
    let currentColor = "lime-400";
</script>

<div
    class="flex flex-col items-center justify-center poppins-regular h-auto p-10 bg-stone-950 text-white sm:p-12 lg:p-20"
>
    <div class="flex flex-col items-center justify-center">
        <h1 class="poppins-bold text-4xl leading-14 tracking-tight sm:text-6xl">
            Hot&Cold
        </h1>
        <div class="text-xl pt-2 sm:text-3xl sm:pt-3 lg:pt-4 inline-flex gap-1.5">
            <h3>Your only friend in</h3>
            <div>
                <ul class=" text-lime-400 poppins-medium">
                    <li><span class="relative">Travelling</span></li>
                    <li><span class="relative">Long work days</span></li>
                    <li><span class="relative">School lunch breaks</span></li>
                </ul>
            </div>
        </div>

    
        <h2 class="flex justify-center poppins-medium text-3xl pt-22 pb-10 sm:text-4xl lg:text-5xl">
            Features
        </h2>
        <div class="grid grid-cols-2 gap-7 sm:grid-cols-3 text-center">
            <div class={flexAllignCenter}>
                <img src="" alt="a" />
                <p>lorem it fili sui apex skibidi sigma</p>
            </div>
            <div class={flexAllignCenter}>
                <img src="" alt="b" />
                <p>lorem it fili sui apex skibidi sigma</p>
            </div>
            <div class={flexAllignCenter}>
                <img src="" alt="c" />
                <p>lorem it fili sui apex skibidi sigma</p>
            </div>
            <div class={flexAllignCenter}>
                <img src="" alt="d" />
                <p>lorem it fili sui apex skibidi sigma</p>
            </div>
            <div class={flexAllignCenter}>
                <img src="" alt="e" />
                <p>lorem it fili sui apex skibidi sigma</p>
            </div>
            <div class={flexAllignCenter}>
                <img src="" alt="f" />
                <p>lorem it fili sui apex skibidi sigma</p>
            </div>
        </div>
    </div>

    <div class="flex flex-col items-center justify-center pt-22">
        <h2 class="poppins-medium text-3xl text-center pb-10 text-lime-400 sm:text-4xl lg:text-5xl">About us</h2>
        <div class="flex flex-col w-[300px] sm:w-[500px] sm:flex sm:justify-center sm:flex-row">
            <div class="flex justify-center"> 
                <img src="" alt="mua" />
            </div>
            <div class="p-2.5 width-[300px] sm:w-[500px]">
                <p>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                    Tenetur voluptas laboriosam animi alias voluptatum
                    necessitatibus quidem, voluptatem, illum neque placeat error
                    sint architecto velit maiores odio sed, illo excepturi fuga.
                </p>
                <p>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                    Tenetur voluptas laboriosam animi alias voluptatum
                    necessitatibus quidem, voluptatem, illum neque placeat error
                    sint architecto velit maiores odio sed, illo excepturi fuga.
                </p>
            </div>
        </div>
    </div>

    <div class="flex flex-col items-center justify-center pt-22">
        <h3 class="poppins-medium text-3xl pb-10 text-center sm:text-4xl lg:text-5xl">Where are we?</h3>
        <div class="grid grid-cols-2 gap-7 text-lime-400 lg:flex lg:justify-evenly">
            <div>
                <img src="" alt="a" />
                <p>Tescoma</p>
            </div>
            <div>
                <img src="" alt="s" />
                <p>Datart</p>
            </div>
            <div>
                <img src="" alt="d" />
                <p>Alza</p>
            </div>
            <div>
                <img src="" alt="f" />
                <p>IKEA</p>
            </div>
        </div>
    </div>

    <div class="flex flex-col items-center justify-center pt-22 text-lime-400">
        <h3 class="poppins-bold text-3xl text-center pb-10 sm:text-4xl lg:text-5xl">Contact</h3>
        <div class="flex flex-row justify-evenly gap-10">
            <img src="" alt="a" />
            <img src="" alt="d" />
            <img src="" alt="d" />
        </div>
    </div>
</div>
