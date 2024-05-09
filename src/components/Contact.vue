<template>
  <div class="container p-5 flex justify-between items-center flex-col lg:flex-row">
    <h1 class="text-3xl font-bold text-center text-cyan-600 underline">
      Contact Us
    </h1>
    <form>
      <div class="flex justify-between items-center gap-4">
        <div class="my-3 flex flex-col">
          <label for="username">Username</label>
          <input
            placeholder="Username"
            class="border border-cyan-600 rounded-md outline-none py-1 px-2"
            type="text"
            id="username"
          />
        </div>

        <div class="my-3 flex flex-col">
          <label for="phone">Phone Number</label>
          <input
            placeholder="Phone Number"
            class="border border-cyan-600 rounded-md outline-none py-1 px-2"
            type="text"
            id="phone"
          />
        </div>
      </div>
      <div class="my-3 flex flex-col">
        <label for="email">Email</label>
        <input
          placeholder="Email"
          class="border border-cyan-600 rounded-md outline-none py-1 px-2"
          type="email"
          id="email"
        />
      </div>

      <div class="flex flex-col">
        <label for="message">Message</label>
        <textarea
          placeholder="Message"
          class="border border-cyan-600 rounded-md outline-none py-1 px-2"
          id="message"
        ></textarea>
      </div>
      <button
        class="bg-cyan-600 text-cyan-50 font-bold mx-auto mt-3 px-2 py-1 w-full hover:bg-cyan-800 duration-300 rounded-md"
      >
        Submit
      </button>
    </form>
  </div>
</template>


