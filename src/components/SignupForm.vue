<template>
    <form>
        <label>Please enter any key</label>
        <input type="name" required v-model="key" maxlength="1">
    <p>You entered the [ {{ key }} ] key.</p>
    </form>

</template>
<script>
export default{
    data(){
        return{
            key: ''
        }
    }
}
</script>
<style>
form{
    max-width: 240px;
    margin: 30px auto;
    background: white;
    text-align: left;
    padding: 40px;
    border-radius: 10px;
background: #e0ccde;
box-shadow:  9px 9px 22px #aa9ba9,
             -9px -9px 22px #fffdff;  

}

label{
    color: rgb(106, 102, 102);
    display: inline-block;
    margin: 25px 0 15px;
    font-size: 0.9em;
    position: relative;
    bottom: 10px;
    display: block;
    margin-left: auto;
    margin-right: auto;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: bold;
    text-align: center;
    text-decoration: underline;
}

input{
    display: block;
    margin-left: auto;
    margin-right: auto;
    padding: 10px 6px;
    width: 60%;
    box-sizing: border-box;
    border: none;
    border-bottom: 1px solid #ddd;
    color: #555;
    outline: none;
    border-radius: 10px;
    text-align: center;
}

button {
    color: #aaa;
    display: inline-block;
    margin: 25px 0 15px;
    font-size: 0.6em;
    display: block;
    margin-left: auto;
    margin-right: auto;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: bold;
}

p{
    text-align: center;
    position: relative;
    top: 10px;
    font-weight: bold;
}
</style>