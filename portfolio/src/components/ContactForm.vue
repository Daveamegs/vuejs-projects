<script></script>

<template>
<form action="" class="contact-form">
    <label for="fullName">Full Name: 
        <input type="text" name="fullName" id="email">
    </label>
    <br>
    <label for="email">Email: 
        <input type="email" name="email" id="email">
    </label>
    <br>

    <textarea name="message" id="message" cols="30" rows="10">
        Please Write Your Message Here...
    </textarea>
    <br>
    <button type="submit">Send</button>
</form>

</template>

<style>
.contact-form{
    display: flex;
    flex-direction: column;
    place-items: center;
}

#message{
    text-align: left;
}
</style>