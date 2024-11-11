# verushash-node

Implementation of the VerushHash V1, V2, V2.1, V2.2 hash algorithm as a node.js module  
Tested for use in node.js v22.11.0


## For testing purposes:

    sudo apt install libsodium-dev
    git clone https://github.com/ComputerGenieCo/verushash-node
    cd verushash-node
    npm install
    node test.js

## Example test.js output (PID  test    hash):

<pre><code>
3798758 VerusHash1   Output 2cd709e6569bd706f14a09e62042ddccfa63bd3725b21f35a8c98adbf4151184 

3798758 VerusHash2   Output 55cec43b110570481f6d565c3a8bb6ed174956494aeebf4c264283791dbd3ded 

3798758 VerusHash2b  Output 248afe7be7771aeb149559d78e4cfffc72f2c937929e493a3d636aa13fbf5cb0 

3798758 VerusHash2b1 Output 0ef8b9530ce44a7ffb9b520daf8fcf59d1d22dd1bfa1a26ef4351d51e37071b7 
</code></pre>