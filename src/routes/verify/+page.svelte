<main class="w-full h-screen overflow-x-hidden overflow-y-hidden grid grid-cols-2 max-sm:overflow-y-auto max-sm:grid-cols-1 max-sm:h-fit">
    <div class="w-full h-full bg-[#000000] flex items-start justify-center px-17.5 py-17.5 relative max-sm:px-7.5 max-sm:pb-50 max-sm:pt-7.5">
        <div class="w-full max-w-100 h-fit flex flex-col items-start justify-start">
            <h1 class="w-fit text-left text-[#ffffff] text-[30px] font-semibold leading-7.75">Menunggu verifikasi</h1>
            <p class="text-[#ffffff] text-[13px] mt-5">Cek informasi pada email anda, dan klik tombol verifikasi di pesan email.</p>
        </div>

        <div class="container">
            <div class="gradientTOP"></div>
        </div>
    </div>

    <div class="scrolledit w-full h-full bg-[#ffffff] flex flex-col px-25 py-17.5 overflow-auto relative z-100 max-sm:overflow-hidden max-sm:px-7.5 max-sm:py-7.5">
        <h1 class="w-fit text-left text-[#1f2328] text-[20px] font-semibold">Sedang menunggu verifikasi</h1>

        <p class="text-[13px] text-[#1f2328] mt-7.5 bg-[#f6f8fa] py-3 px-3 rounded-[5px] border-[1.5px] border-[#d5dce3] border-l-3 border-l-[#d5dce3]">Verifikasi akan <span class="font-semibold">kadaluarsa di 10 menit kedepan</span>, segera verifikasi email anda untuk melanjutkan proses. Jika anda tidak memverifikasi email anda selama 1 hari maka akun akan di hapus dari temporary users, dan anda wajib melakukan register ulang.</p>

        <button onclick={() => window.location.href="https://mail.google.com/"} class="w-full py-2.5 text-center bg-[#1f883d] text-[#ffffff] font-semibold rounded-[5px] mt-7 cursor-pointer">Buka gmail</button>
    </div>
</main>

<style>
    .container {
        width: 100%;
        height: 100%;
        position: absolute;
        bottom: -70%;
        opacity: 0.5;
        --u: 5px;
        --c1: #ffffff;
        --c2: #1f2328;
        --c3: #1f883d;
        --gp: 50% / calc(var(--u) * 16.9) calc(var(--u) * 12.8);
        background: conic-gradient(
                from 122deg at 50% 85.15%,
                var(--c2) 0 58deg,
                var(--c3) 0 116deg,
                #fff0 0 100%
            )
            var(--gp),
            conic-gradient(from 122deg at 50% 72.5%, var(--c1) 0 116deg, #fff0 0 100%)
            var(--gp),
            conic-gradient(from 58deg at 82.85% 50%, var(--c3) 0 64deg, #fff0 0 100%)
            var(--gp),
            conic-gradient(
                from 58deg at 66.87% 50%,
                var(--c1) 0 64deg,
                var(--c2) 0 130deg,
                #fff0 0 100%
            )
            var(--gp),
            conic-gradient(from 238deg at 17.15% 50%, var(--c2) 0 64deg, #fff0 0 100%)
            var(--gp),
            conic-gradient(
                from 172deg at 33.13% 50%,
                var(--c3) 0 66deg,
                var(--c1) 0 130deg,
                #fff0 0 100%
            )
            var(--gp),
            linear-gradient(98deg, var(--c3) 0 15%, #fff0 calc(15% + 1px) 100%)
            var(--gp),
            linear-gradient(-98deg, var(--c2) 0 15%, #fff0 calc(15% + 1px) 100%)
            var(--gp),
            conic-gradient(
                from -58deg at 50.25% 14.85%,
                var(--c3) 0 58deg,
                var(--c2) 0 116deg,
                #fff0 0 100%
            )
            var(--gp),
            conic-gradient(from -58deg at 50% 28.125%, var(--c1) 0 116deg, #fff0 0 100%)
            var(--gp),
            linear-gradient(90deg, var(--c2) 0 50%, var(--c3) 0 100%) var(--gp);
    }

    .gradientTOP {
        width: 100%;
        height: 100px;
        position: absolute;
        top: 0;
        background: linear-gradient(
            to bottom,
            #000000 0%,
            transparent 100%
        );
    }
</style>