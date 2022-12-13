<script>
    import { onMount } from "svelte";
    import lottie from "lottie-web";

    /**
     * @type {any}
     */
    let scroll;

    /**
     * @param {number} scroll
     */
    function getRockPostion(scroll) {
        return Math.min(scroll * 1.25, 1200);
    }

    /**
     * @type {HTMLElement}
     */
    let crane_animation_contaner;
    onMount(async function () {
        lottie.loadAnimation({
            container: crane_animation_contaner,
            path: "https://assets5.lottiefiles.com/packages/lf20_VWz8YDBMOZ.json",
            rendererSettings: {
                progressiveLoad: true, // Boolean, only svg renderer, loads dom elements when needed. Might speed up initialization for large number of elements.
            },
        });
    });
</script>

<svelte:window
    bind:scrollY={scroll}
    on:scroll={() => {
        console.log(scroll);
    }}
/>

<section id="head">
    <!-- <div> -->

    <svg
        xmlns:xlink="http://www.w3.org/1999/xlink"
        width="247.5"
        xmlns="http://www.w3.org/2000/svg"
        height="239"
        overflow="visible"
        id="screenshot-e2677fc7-f8ce-802a-8001-bceab585afd9"
        viewBox="-6 -6 190 220"
        style="-webkit-print-color-adjust: exact;"
        fill="none"
        version="1.1"
        ><g id="shape-e2677fc7-f8ce-802a-8001-bceab585afd9" rx="0" ry="0"
            ><g id="shape-e2677fc7-f8ce-802a-8001-bcc8be000c0a"
                ><defs
                    ><filter
                        id="filter_49a9d398-29e7-80d4-8001-bceb5749b8d6"
                        x="-1.4877447946247222"
                        y="-0.4527918940162208"
                        width="4.546918160678014"
                        height="2.0794968315107023"
                        filterUnits="objectBoundingBox"
                        color-interpolation-filters="sRGB"
                        ><feFlood
                            flood-opacity="0"
                            result="BackgroundImageFix"
                        /><feColorMatrix
                            in="SourceAlpha"
                            type="matrix"
                            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                        /><feOffset dx="4" dy="4" /><feGaussianBlur
                            stdDeviation="2"
                        /><feColorMatrix
                            type="matrix"
                            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"
                        /><feBlend
                            mode="normal"
                            in2="BackgroundImageFix"
                            result="filter_e2677fc7-f8ce-802a-8001-bcd2ef007e75"
                        /><feBlend
                            mode="normal"
                            in="SourceGraphic"
                            in2="filter_e2677fc7-f8ce-802a-8001-bcd2ef007e75"
                            result="shape"
                        /></filter
                    ><filter
                        id="filter_shadow_49a9d398-29e7-80d4-8001-bceb5749b8d6"
                        x="-1.4877447946247222"
                        y="-0.4527918940162208"
                        width="4.546918160678014"
                        height="2.0794968315107023"
                        filterUnits="objectBoundingBox"
                        color-interpolation-filters="sRGB"
                        ><feFlood
                            flood-opacity="0"
                            result="BackgroundImageFix"
                        /><feColorMatrix
                            in="SourceAlpha"
                            type="matrix"
                            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                        /><feOffset dx="4" dy="4" /><feGaussianBlur
                            stdDeviation="2"
                        /><feColorMatrix
                            type="matrix"
                            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"
                        /><feBlend
                            mode="normal"
                            in2="BackgroundImageFix"
                            result="filter_e2677fc7-f8ce-802a-8001-bcd2ef007e75"
                        /><feBlend
                            mode="normal"
                            in="SourceGraphic"
                            in2="filter_e2677fc7-f8ce-802a-8001-bcd2ef007e75"
                            result="shape"
                        /></filter
                    ></defs
                ><g id="fills-e2677fc7-f8ce-802a-8001-bcc8be000c0a"
                    ><rect
                        rx="0"
                        ry="0"
                        x="153"
                        y="35"
                        transform="matrix(0.999983,0.005827,-0.005827,0.999983,0.407746,-0.951519)"
                        width="21"
                        height="69"
                        filter="url(#filter_49a9d398-29e7-80d4-8001-bceb5749b8d6)"
                    /></g
                ><g
                    id="strokes-e2677fc7-f8ce-802a-8001-bcc8be000c0a"
                    filter="url(#filter_49a9d398-29e7-80d4-8001-bceb5749b8d6)"
                    ><g class="stroke-shape"
                        ><rect
                            rx="0"
                            ry="0"
                            x="153"
                            y="35"
                            width="21"
                            height={69 + getRockPostion(scroll)}
                            style="fill: none; stroke-width: 6; stroke: rgb(130, 136, 134); stroke-opacity: 1;"
                        /></g
                    ></g
                ></g
            ><g id="shape-e2677fc7-f8ce-802a-8001-bcc92a999055"
                ><defs
                    ><filter
                        id="filter_49a9d398-29e7-80d4-8001-bceb574cec7b"
                        x="-0.6067415730337079"
                        y="-0.3698630136986301"
                        width="2.4831460674157304"
                        height="1.904109589041096"
                        filterUnits="objectBoundingBox"
                        color-interpolation-filters="sRGB"
                        ><feFlood
                            flood-opacity="0"
                            result="BackgroundImageFix"
                        /><feColorMatrix
                            in="SourceAlpha"
                            type="matrix"
                            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                        /><feOffset dx="4" dy="4" /><feGaussianBlur
                            stdDeviation="2"
                        /><feColorMatrix
                            type="matrix"
                            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"
                        /><feBlend
                            mode="normal"
                            in2="BackgroundImageFix"
                            result="filter_e2677fc7-f8ce-802a-8001-bcd2e3b0100b"
                        /><feBlend
                            mode="normal"
                            in="SourceGraphic"
                            in2="filter_e2677fc7-f8ce-802a-8001-bcd2e3b0100b"
                            result="shape"
                        /></filter
                    ><filter
                        id="filter_shadow_49a9d398-29e7-80d4-8001-bceb574cec7b"
                        x="-0.6067415730337079"
                        y="-0.3698630136986301"
                        width="2.4831460674157304"
                        height="1.904109589041096"
                        filterUnits="objectBoundingBox"
                        color-interpolation-filters="sRGB"
                        ><feFlood
                            flood-opacity="0"
                            result="BackgroundImageFix"
                        /><feColorMatrix
                            in="SourceAlpha"
                            type="matrix"
                            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                        /><feOffset dx="4" dy="4" /><feGaussianBlur
                            stdDeviation="2"
                        /><feColorMatrix
                            type="matrix"
                            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.2 0"
                        /><feBlend
                            mode="normal"
                            in2="BackgroundImageFix"
                            result="filter_e2677fc7-f8ce-802a-8001-bcd2e3b0100b"
                        /><feBlend
                            mode="normal"
                            in="SourceGraphic"
                            in2="filter_e2677fc7-f8ce-802a-8001-bcd2e3b0100b"
                            result="shape"
                        /></filter
                    ></defs
                ><g id="rock"
                    ><rect
                        width="44.5"
                        height="73"
                        x="141"
                        transform="matrix(1,0,0,1,0,0)"
                        style="fill: rgb(54, 75, 74);"
                        ry="0"
                        rx="0"
                        filter="url(#filter_49a9d398-29e7-80d4-8001-bceb574cec7b)"
                        y={104 + getRockPostion(scroll)}
                    /></g
                ></g
            ><g id="shape-e2677fc7-f8ce-802a-8001-bce6ecf89fed"
                ><g id="fills-e2677fc7-f8ce-802a-8001-bce6ecf89fed"
                    ><path rx="0" ry="0" d="M0,194L0,0L38,0L38,194" /></g
                ><g id="strokes-e2677fc7-f8ce-802a-8001-bce6ecf89fed"
                    ><g class="stroke-shape"
                        ><path
                            rx="0"
                            ry="0"
                            d="M0,194L0,0L38,0L38,194"
                            style="fill: none; stroke-width: 12; stroke: rgb(166, 219, 251); stroke-opacity: 1;"
                        /></g
                    ></g
                ></g
            ><g id="shape-e2677fc7-f8ce-802a-8001-bcc82f30963f"
                ><g id="fills-e2677fc7-f8ce-802a-8001-bcc82f30963f"
                    ><path
                        rx="0"
                        ry="0"
                        d="M1,0L194,0L194,35L52.611,35L29.004,35"
                        style="fill: rgb(14, 43, 60); fill-opacity: 1;"
                    /></g
                ><g id="strokes-e2677fc7-f8ce-802a-8001-bcc82f30963f"
                    ><g class="stroke-shape"
                        ><path
                            rx="0"
                            ry="0"
                            d="M1,0L194,0L194,35L52.611,35L29.004,35"
                            style="fill: none; stroke-width: 12; stroke: rgb(166, 219, 251); stroke-opacity: 1;"
                        /></g
                    ></g
                ></g
            ></g
        ></svg
    >
    <h1>بطارية الجاذبية</h1>
    <a href="#table">
        <svg
            xmlns:xlink="http://www.w3.org/1999/xlink"
            width="51"
            xmlns="http://www.w3.org/2000/svg"
            height="66"
            id="screenshot-e2677fc7-f8ce-802a-8001-bccb23dc6c52"
            viewBox="1065.5 937 51 66"
            style="bottom: 50;position: absolute; -webkit-print-color-adjust: exact;"
            fill="none"
            version="1.1"
            ><g id="shape-e2677fc7-f8ce-802a-8001-bccb23dc6c52"
                ><g id="fills-e2677fc7-f8ce-802a-8001-bccb23dc6c52"
                    ><path
                        rx="0"
                        ry="0"
                        d="M1065.5,982.343L1065.5,1003L1116.5,1003L1116.5,982.343L1106.3,982.343L1106.3,992.671L1096.1,992.671L1096.1,951.357L1085.9,951.357L1085.9,992.671L1075.7,992.671L1075.7,982.343L1065.5,982.343ZM1085.39,937"
                        style="fill: rgb(222, 235, 244); fill-opacity: 1;"
                    /></g
                ></g
            ></svg
        >
    </a>
</section>

<section id="table">
    <h2>الفهرس</h2>
    <div>
        <a href="#main"><h3>المقدمة</h3></a>

        <a href="#prob"><h3>المشكلة</h3></a>

        <a href="#how"><h3>كيف تعمل بطارية الجاذبية</h3></a>

        <a href="#end"><h3>الختام</h3></a>
    </div>
</section>

<section id="main">
    <h2>المقدمة</h2>
    <div>
        <p>بسم الله الرحمن الرحيم</p>
        <p>لا يخلو منزل ومجتمع من الكهرباء في هذا الزمن</p>
        <p>
            فأصبح توليد الطاقة وتخزينها من أكبر مجالات البحث والابتكار في
            السنوات الأخيرة
        </p>
        <p>فبدأنا نرى بعض الافكار المبتكرة في حفظ الطاقة على نطاق واسع</p>
    </div>
</section>

<section id="prob">
    <h2>المشكلة</h2>
    <div>
        <p>وسائل توليد الطاقة المتجددة لا تولد الطاقة بشكل ثابت خلال اليوم</p>
        <p>مثلا الألواح الشمسية تولد طاقة أكثر من الاستهلاك في ظهيرة</p>
        <p>فيتم تخزين الطاقة الزائدة في بطاريات بأشكال مختلفة</p>
    </div>
</section>

<div style="height: 150vh;">
    <section style="text-align: center;">
        <h2>ومـن هـذه الاشكال<br /><u>بــطـارية الجـاذبية</u></h2>
    </section>
</div>

<section id="how">
    <h2>كيف تعمل بطارية الجاذبية؟</h2>
    <div>
        <p>
            تعمل بطارية الجاذبية عن طريق استغلال الطاقة الزائدة في شبكة الكهرباء
            لرفع اثقال فيتولد فيها طاقة وضع وعند الحاجة للطاقة يتم انزال الثقل
            باستخدام مولد كهربائي
        </p>
        <div bind:this={crane_animation_contaner} />
    </div>
</section>

<section id="end">
    <h2>وفي الختام</h2>
    <p class="words" style="font-size:25px">
        بطارية الجاذبية ليست مثالية, لكن لو تطورت يمكن اعتبارها حل واقعي لمشكلة
        كبيرة في مجال الطاقة
    </p>
    <h2>عمل الطالب يزن حمزه</h2>
</section>
{#if scroll >= 1800}
<a href="#table">\
    <svg
xmlns:xlink="http://www.w3.org/1999/xlink"
xmlns="http://www.w3.org/2000/svg"
height="55"
id="screenshot-e2677fc7-f8ce-802a-8001-bccb23dc6c52"
viewBox="1065.5 937 51 66"
style="bottom: 5px; right: 35px; -webkit-transform: scaleY(-1);transform: scaleY(-1);bottom: 50;position: fixed; -webkit-print-color-adjust: exact;"
fill="none"
version="1.1"
><g id="shape-e2677fc7-f8ce-802a-8001-bccb23dc6c52"
    ><g id="fills-e2677fc7-f8ce-802a-8001-bccb23dc6c52"
        ><path
            rx="0"
            ry="0"
            d="M1065.5,982.343L1065.5,1003L1116.5,1003L1116.5,982.343L1106.3,982.343L1106.3,992.671L1096.1,992.671L1096.1,951.357L1085.9,951.357L1085.9,992.671L1075.7,992.671L1075.7,982.343L1065.5,982.343ZM1085.39,937"
            style="fill: rgb(222, 235, 244); fill-opacity: 1;"
        /></g
    ></g
></svg
>
</a>

{/if}
