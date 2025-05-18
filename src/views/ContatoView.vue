<template>
    <section class="bg-gray-100 py-12 px-4 sm:px-6 lg:px-8">
        <h1 class="text-3xl text-left px-16 py-2 text-black"><strong>Entre em contato comigo!</strong></h1>
        <h1 class="text-xl text-left px-16 py-2">Tire suas duvidas, faça orçamentos e contrate meus serviços por aqui.</h1>
        <div class="max-w-2xl mx-auto bg-white shadow-xl rounded-2xl p-8">
            <h2 class="text-xl font-bold mb-6 text-gray-800">Preencha os campos</h2>
            <form action="#" method="POST" class="space-y-6">
                <div>
                    <label for="name" class="block text-sm font-medium text-gray-700">Nome</label>
                    <input type="text" id="nome" name="nome" required
                    class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-lg shadow-sm" />
                </div>
                <div>
                    <label for="email" class="block text-sm font-medium text-gray-700">Email</label>
                    <input type="email" id="email" name="email" required
                    class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-lg shadow-sm" />
                </div>
                <div>
                    <label for="message" class="block text-sm font-medium text-gray-700">Mensagem</label>
                    <textarea id="messagem" name="messagem" rows="5" required
                    class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-lg shadow-sm"></textarea>
                </div>
                <div>
                    <a class="w-full bg-rose-600 text-white py-2 px-4 rounded-lg hover:bg-rose-800 transition duration-200 cursor-pointer">Enviar Mensagem</a>
                </div>
            </form>
        </div>
    </section>
</template>