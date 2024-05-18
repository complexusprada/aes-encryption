<script setup></script>

<template>
  <section class="section mx-auto">
    <div>

      <h1 class="text-center text-3xl font-medium my-14">AES Encryption and Decryption</h1>
      <div class="grid grid-cols-2 gap-x-40">
        <div>
        <div class="form-group-textarea">
          <label>Enter text to be Encrypted</label>
        <textarea class="textarea" placeholder="Enter text . . ."></textarea>
        </div>
        <div class="form-group">
          <label>Select Cipher Mode of Encryption</label>
          <select class="select">
            <option value="ECB" selected>ECB</option>
            <option value="CBC">CBC</option>
          </select>
        </div>
        <div class="form-group">
          <label>Key Size in Bits</label>
          <select class="select">
            <option value="128" selected>128</option>
            <option value="192">192</option>
            <option value="256">256</option>
          </select>
        </div>
        <div class="form-group">
          <label>Enter Secret Key</label>
          <input type="text" class="input" placeholder="Enter key . . ." />
        </div>
        <div class="mb-4">
          <label class="mr-3">Output Text Format:</label>
          <input type="radio" value="Base64" />Base64
          <input type="radio" value="Hex" />Hex
        </div>

        <button class="btn" type="button">Encrypt</button>

        <div class="form-group-textarea">
          <label>AES Encrypted Output:</label>
        <textarea class="textarea" placeholder="Enter text . . ."></textarea>
        </div>
      </div>

      

      <div>
        <div class="form-group-textarea">
          <label>Enter text to be Decrypted</label>
        <textarea class="textarea" placeholder="Enter text . . ."></textarea>
        </div>
        <div class="mb-4">
          <label class="mr-3">Output Text Format:</label>
          <input type="radio" value="Base64" />Base64
          <input type="radio" value="Hex" />Hex
        </div>
        <div class="form-group">
          <label>Select Cipher Mode of Decryption</label>
          <select class="select">
            <option value="ECB" selected>ECB</option>
            <option value="CBC">CBC</option>
          </select>
        </div>
        <div class="form-group">
          <label>Key Size in Bits</label>
          <select class="select">
            <option value="128" selected>128</option>
            <option value="192">192</option>
            <option value="256">256</option>
          </select>
        </div>
        <div class="form-group">
          <label>Enter Secret Key</label>
          <input type="text" class="input" placeholder="Enter key . . ." />
        </div>
        

        <button class="btn" type="button">Decrypt</button>
        <div class="form-group-textarea">
          <label>AES Encrypted Output:</label>
        <textarea class="textarea" placeholder="Enter text . . ."></textarea>
        </div>
      </div>
      </div>
      
    </div>
  </section>
</template>

<style></style>
