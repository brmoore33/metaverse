# metaverse

// Every time that I run a truffle test after starting my ganache blockchain, I get this..
//

PS C:\Users\braxt\metaverse> truffle test
Using network 'development'.


Compiling your contracts...
===========================
> Compiling @openzeppelin\contracts\token\ERC721\ERC721.sol
> Compiling @openzeppelin\contracts\token\ERC721\IERC721.sol
> Compiling @openzeppelin\contracts\token\ERC721\IERC721Receiver.sol  
> Compiling @openzeppelin\contracts\token\ERC721\extensions\IERC721Metadata.sol
> Compiling @openzeppelin\contracts\utils\Address.sol
> Compiling @openzeppelin\contracts\utils\Context.sol
> Compiling @openzeppelin\contracts\utils\Strings.sol
> Compiling @openzeppelin\contracts\utils\introspection\ERC165.sol    
> Compiling @openzeppelin\contracts\utils\introspection\IERC165.sol   
> Compiling .\src\contracts\Land.sol
> Compiling .\src\contracts\Migrations.sol
> Artifacts written to C:\Users\braxt\AppData\Local\Temp\test--17304-sJ0PQjp7KAaF
> Compiled successfully using:
   - solc: 0.8.2+commit.661d1103.Emscripten.clang


  0 passing (1ms)
  
  It is supposed to be testing my smart contracts such as my transfers, minting, and deployment and then say "14 passing", but I am not sure what went wrong..
I put my smart contracts in here that I created land.test.js and Land.sol.. if you guys could give it a look that'd be great.
