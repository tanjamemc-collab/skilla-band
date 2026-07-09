<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SKILLa Band - วงดนตรีรับงานแสดงสดทุกประเภท</title>
    <!-- Tailwind CSS สำหรับตกแต่งหน้าเว็บ -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome สำหรับไอคอนสวยๆ -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Google Fonts - Prompt -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Prompt:wght@300;400;500;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Prompt', sans-serif; }
    </style>
</head>
<body class="bg-zinc-950 text-zinc-100 scroll-smooth">

    <!-- 1. แถบเมนูด้านบน (Navigation Bar) -->
    <nav class="fixed w-full z-50 bg-zinc-950/80 backdrop-blur-md border-b border-zinc-800">
        <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold tracking-wider text-amber-500"><i class="fa-solid fa-guitar mr-2"></i>SKILLa Band</a>
            <div class="hidden md:flex space-x-8">
                <a href="#home" class="hover:text-amber-500 transition">หน้าแรก</a>
                <a href="#about" class="hover:text-amber-500 transition">รู้จักเรา</a>
                <a href="#videos" class="hover:text-amber-500 transition">ผลงานการแสดง</a>
                <a href="#reviews" class="hover:text-amber-500 transition">รีวิวลูกค้า</a>
                <a href="#contact" class="hover:text-amber-500 transition">ติดต่องาน</a>
            </div>
            <a href="#contact" class="bg-amber-500 hover:bg-amber-600 text-zinc-950 font-bold px-5 py-2 rounded-full transition shadow-lg shadow-amber-500/20">จ้างงานเลย</a>
        </div>
    </nav>

    <!-- 2. ส่วนหัวเว็บไซต์ (Hero Section) -->
    <header id="home" class="relative h-screen flex items-center justify-center text-center px-4 overflow-hidden">
        <!-- ภาพพื้นหลังแบบจางๆ -->
        <div class="absolute inset-0 bg-[url('data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAYEBQYFBAYGBQYHBwYIChAKCgkJChQODwwQFxQYGBcUFhYaHSUfGhsjHBYWICwgIyYnKSopGR8tMC0oMCUoKSj/2wBDAQcHBwo[...]
        <div class="absolute inset-0 bg-gradient-to-t from-zinc-950 via-zinc-950/50 to-transparent"></div>
        
        <div class="relative z-10 max-w-3xl">
            <span class="text-amber-500 font-medium tracking-widest uppercase block mb-3">Live Music Experience</span>
            <h1 class="text-4xl md:text-6xl font-bold mb-6 leading-tight">เติมเต็มความมันส์ให้งานของคุณด้วย <span class="text-transpar[...]
            <p class="text-zinc-400 text-lg md:text-xl mb-8">รับงานแสดงสด งานแต่งงาน งานเลี้ยงบริษัท ปาร์ตี้ส�[...]
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#videos" class="border border-zinc-700 hover:bg-zinc-800 px-8 py-3 rounded-full font-medium transition"><i class="fa-regular fa-circle-play mr-2"></i>ดูคลิปผล�[...]
                <a href="#contact" class="bg-amber-500 hover:bg-amber-600 text-zinc-950 px-8 py-3 rounded-full font-bold transition shadow-lg shadow-amber-500/20">เช็กคิวงานภา�[...]
            </div>
        </div>
    </header>

    <!-- 3. เกี่ยวกับวงและประเภทงาน (About & Services) -->
    <section id="about" class="py-24 max-w-6xl mx-auto px-4">
        <div class="text-center mb-16">
            <h2 class="text-3xl font-bold mb-4">บริการและรูปแบบวงดนตรี</h2>
            <p class="text-zinc-400">เราปรับเปลี่ยนรูปแบบเครื่องดนตรีให้เหมาะสมกับขนาดงานแล�[...]
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- รูปแบบ 1 -->
            <div class="bg-zinc-900 border border-zinc-800 p-8 rounded-2xl hover:border-amber-500/50 transition group">
                <div class="w-12 h-12 bg-amber-500/10 text-amber-500 rounded-xl flex items-center justify-center text-xl mb-6 group-hover:bg-amber-500 group-hover:text-zinc-950 transition-all duration[...]
                    <i class="fa-solid fa-guitar"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Acoustic Trio</h3>
                <p class="text-zinc-400 text-sm leading-relaxed mb-4">นักร้อง, กีตาร์โปร่ง, คาฮอน เหมาะสำหรับงานแต่ง��[...]
                <span class="text-amber-500 font-semibold text-sm">ยอดนิยมสำหรับงานแต่งงาน &rarr;</span>
            </div>
            <!-- รูปแบบ 2 -->
            <div class="bg-zinc-900 border border-zinc-800 p-8 rounded-2xl hover:border-amber-500/50 transition group">
                <div class="w-12 h-12 bg-amber-500/10 text-amber-500 rounded-xl flex items-center justify-center text-xl mb-6 group-hover:bg-amber-500 group-hover:text-zinc-950 transition-all duration[...]
                    <i class="fa-solid fa-drum"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Full Band</h3>
                <p class="text-zinc-400 text-sm leading-relaxed mb-4">จัดเต็มเครื่องดนตรีสากลครบชิ้น กีตาร์ เบส กลอ�[...]
                <span class="text-amber-500 font-semibold text-sm">เหมาะสำหรับงาน After Party &rarr;</span>
            </div>
            <!-- รูปแบบ 3 -->
            <div class="bg-zinc-900 border border-zinc-800 p-8 rounded-2xl hover:border-amber-500/50 transition group">
                <div class="w-12 h-12 bg-amber-500/10 text-amber-500 rounded-xl flex items-center justify-center text-xl mb-6 group-hover:bg-amber-500 group-hover:text-zinc-950 transition-all duration[...]
                    <i class="fa-solid fa-sliders"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Custom Band + คุมระบบเสียง</h3>
                <p class="text-zinc-400 text-sm leading-relaxed mb-4">บริการให้เช่าเครื่องเสียงระบบไฟระดับคอนเสิร�[...]
                <span class="text-amber-500 font-semibold text-sm">บริการครบวงจรจบในที่เดียว &rarr;</span>
            </div>
        </div>
    </section>

    <!-- 4. ส่วนแสดงคลิปผลงาน (Video Gallery Section) -->
    <section id="videos" class="py-24 bg-zinc-900/50 border-y border-zinc-800">
        <div class="max-w-6xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold mb-4">คลิปผลงานการแสดงสด</h2>
                <p class="text-zinc-400">ชมบรรยากาศความสนุก หน้าเวทีจริง เพื่อประกอบการตัดสินใจ�[...]
            </div>

            <!-- วิดีโอหลักขนาดใหญ่ -->
            <div class="mb-12">
                <div class="aspect-video w-full max-w-4xl mx-auto rounded-2xl overflow-hidden shadow-2xl border border-zinc-800 bg-zinc-950 relative flex items-center justify-center">
                    <iframe class="w-full h-full absolute inset-0" src="https://www.youtube.com/embed/BTwFJn9c-Lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboar[...]
                </div>
                <div class="text-center mt-4">
                    <p class="text-amber-500 font-medium"><i class="fa-solid fa-star mr-2"></i>คลิปไฮไลท์การแสดงสดหน้างานจริง</p>
                </div>
            </div>

            <!-- วิดีโอย่อย (ตาราง 2 คอลัมน์) -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                <div>
                    <div class="aspect-video rounded-xl overflow-hidden border border-zinc-800 bg-zinc-950">
                        <iframe class="w-full h-full" src="https://www.youtube.com/embed/5SoigaCqbg0" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
                    </div>
                    <p class="mt-3 text-sm text-zinc-400 font-medium"><i class="fa-solid fa-music mr-2 text-amber-500"></i>คลิปแสดงสดหน้างานจริง</p>
                </div>
                <div>
                    <div class="aspect-video rounded-xl overflow-hidden border border-zinc-800 bg-zinc-950">
                        <iframe class="w-full h-full" src="https://www.youtube.com/embed/8-2afXsdkWo" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
                    </div>
                    <p class="mt-3 text-sm text-zinc-400 font-medium"><i class="fa-solid fa-bolt mr-2 text-amber-500"></i>คลิปแสดงสดหน้างานจริง</p>
                </div>
                <div>
                    <div class="aspect-video rounded-xl overflow-hidden border border-zinc-800 bg-zinc-950">
                        <iframe class="w-full h-full" src="https://www.youtube.com/embed/R8GfvBDJW9U" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
                    </div>
                    <p class="mt-3 text-sm text-zinc-400 font-medium"><i class="fa-solid fa-microphone mr-2 text-amber-500"></i>คลิปแสดงสดหน้างานจริง</p>
                </div>
                <div>
                    <div class="aspect-video rounded-xl overflow-hidden border border-zinc-800 bg-zinc-950">
                        <iframe class="w-full h-full" src="https://www.youtube.com/embed/3TZnArf06sM" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
                    </div>
                    <p class="mt-3 text-sm text-zinc-400 font-medium"><i class="fa-solid fa-guitar mr-2 text-amber-500"></i>คลิปแสดงสดหน้างานจริง</p>
                </div>
                <div class="md:col-span-2">
                    <div class="aspect-video rounded-xl overflow-hidden border border-zinc-800 bg-zinc-950 max-w-md mx-auto">
                        <iframe class="w-full h-full" src="https://www.youtube.com/embed/otJo53Uju7Q" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
                    </div>
                    <p class="mt-3 text-sm text-zinc-400 font-medium text-center"><i class="fa-solid fa-heart mr-2 text-amber-500"></i>เพลง "ปลายฟ้า" ขับร้องโด�[...]
                </div>
            </div>
        </div>
    </section>

    <!-- 4.5 รีวิวจากลูกค้า (Testimonials Section) -->
    <section id="reviews" class="py-24 max-w-6xl mx-auto px-4">
        <div class="text-center mb-16">
            <span class="text-amber-500 font-medium tracking-wider uppercase block mb-2">Testimonials</span>
            <h2 class="text-3xl font-bold mb-4">เสียงตอบรับจากลูกค้าที่เคยจ้างงาน</h2>
            <p class="text-zinc-400">ความประทับใจจากเจ้าภาพงานและองค์กรที่ไว้วางใจให้เราดูแ�[...]
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- รีวิว 1 -->
            <div class="bg-zinc-900 border border-zinc-800 p-8 rounded-2xl">
                <div class="flex gap-1 text-amber-500 mb-4">
                    <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                </div>
                <p class="text-zinc-300 text-sm leading-relaxed mb-6">"วงเล่นสดดีมาก คุมบรรยากาศงานแต่งได้ตามที่ต้��[...]
                <div class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-full bg-amber-500/10 text-amber-500 flex items-center justify-center font-bold">พ</div>
                    <div>
                        <p class="font-semibold text-sm">คุณพลอย ศิริวัฒน์</p>
                        <p class="text-xs text-zinc-500">เจ้าภาพงานแต่งงาน</p>
                    </div>
                </div>
            </div>
            <!-- รีวิว 2 -->
            <div class="bg-zinc-900 border border-zinc-800 p-8 rounded-2xl">
                <div class="flex gap-1 text-amber-500 mb-4">
                    <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                </div>
                <p class="text-zinc-300 text-sm leading-relaxed mb-6">"จ้างวงมาเล่นงานเลี้ยงปีใหม่บริษัท พนักงานสน��[...]
                <div class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-full bg-amber-500/10 text-amber-500 flex items-center justify-center font-bold">ก</div>
                    <div>
                        <p class="font-semibold text-sm">คุณกิตติ เจริญสุข</p>
                        <p class="text-xs text-zinc-500">ฝ่าย HR บริษัทเอกชน</p>
                    </div>
                </div>
            </div>
            <!-- รีวิว 3 -->
            <div class="bg-zinc-900 border border-zinc-800 p-8 rounded-2xl">
                <div class="flex gap-1 text-amber-500 mb-4">
                    <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                </div>
                <p class="text-zinc-300 text-sm leading-relaxed mb-6">"ประทับใจตั้งแต่วันคุยงานจนถึงวันแสดงจริง มื��[...]
                <div class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-full bg-amber-500/10 text-amber-500 flex items-center justify-center font-bold">น</div>
                    <div>
                        <p class="font-semibold text-sm">คุณนภัส ทองดี</p>
                        <p class="text-xs text-zinc-500">ผู้จัดงานอีเวนต์</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. ช่องทางการติดต่อจ้างงาน (Contact Section) -->
    <section id="contact" class="py-24 max-w-6xl mx-auto px-4">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
            <!-- ข้อมูลติดต่อด่วน -->
            <div>
                <span class="text-amber-500 font-medium tracking-wider uppercase block mb-2">Contact Us</span>
                <h2 class="text-3xl md:text-4xl font-bold mb-6">สนใจจ้างงานวงดนตรี สรุปราคาได้ทันที</h2>
                <p class="text-zinc-400 mb-8 leading-relaxed">กรุณาแจ้งรายละเอียด <strong>วันที่ เวลา สถานที่ และรูป[...]
                
                <div class="space-y-6">
                    <a href="tel:0891234567" class="flex items-center gap-4 bg-zinc-900 p-4 rounded-xl border border-zinc-800 hover:border-amber-500/50 transition">
                        <div class="w-10 h-10 bg-amber-500/10 text-amber-500 rounded-full flex items-center justify-center">
                            <i class="fa-solid fa-phone"></i>
                        </div>
                        <div>
                            <p class="text-xs text-zinc-500">โทรศัพท์</p>
                            <p class="font-semibold">095-123-8215</p>
                        </div>
                    </a>
                    <a href="https://line.me/ti/p/~zom99" target="_blank" rel="noopener noreferrer" class="flex items-center gap-4 bg-zinc-900 p-4 rounded-xl border border-zinc-800 hover:border-amber-[...]
                        <div class="w-10 h-10 bg-amber-500/10 text-amber-500 rounded-full flex items-center justify-center">
                            <i class="fa-brands fa-line"></i>
                        </div>
                        <div>
                            <p class="text-xs text-zinc-500">LINEID</p>
                            <p class="font-semibold">zom99</p>
                        </div>
                    </a>
                    <a href="#" class="flex items-center gap-4 bg-zinc-900 p-4 rounded-xl border border-zinc-800 hover:border-amber-500/50 transition">
                        <div class="w-10 h-10 bg-amber-500/10 text-amber-500 rounded-full flex items-center justify-center">
                            <i class="fa-brands fa-facebook-f"></i>
                        </div>
                        <div>
                            <p class="text-xs text-zinc-500">Facebook Page</p>
                            <p class="font-semibold">SKILLa Band</p>
                        </div>
                    </a>
                </div>
            </div>

            <!-- ฟอร์มติดต่อ -->
            <div class="bg-zinc-900 border border-zinc-800 rounded-2xl p-8">
                <h3 class="text-xl font-bold mb-6">ส่งรายละเอียดงานให้เรา</h3>
                <div class="space-y-4">
                    <input type="text" placeholder="ชื่อ-นามสกุล" class="w-full bg-zinc-950 border border-zinc-800 rounded-lg px-4 py-3 text-sm focus:outline-none focus:border-am[...]
                    <input type="text" placeholder="วันที่จัดงาน" class="w-full bg-zinc-950 border border-zinc-800 rounded-lg px-4 py-3 text-sm focus:outline-none focus:border-[...]
                    <input type="text" placeholder="สถานที่จัดงาน" class="w-full bg-zinc-950 border border-zinc-800 rounded-lg px-4 py-3 text-sm focus:outline-none focus:bord[...]
                    <textarea placeholder="รายละเอียดเพิ่มเติม เช่น รูปแบบงาน จำนวนแขก" rows="4" class="w-full bg-zinc-9[...]
                    <button class="w-full bg-amber-500 hover:bg-amber-600 text-zinc-950 font-bold py-3 rounded-lg transition">ส่งข้อมูลติดต่อ</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-zinc-800 py-8">
        <div class="max-w-6xl mx-auto px-4 text-center text-zinc-500 text-sm">
            &copy; 2026 SKILLa Band. สงวนลิขสิทธิ์ทุกประการ.
        </div>
    </footer>

</body>
</html>