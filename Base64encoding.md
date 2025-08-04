# Base64 Encoding

## What is Base64 Encoding?
- Base64 encoding is a method of converting binary data into an ASCII string format using a set of 64 characters.

## What are the key components of Base64 Encoding?

- Encoding Process
- Character Set
- Padding
- Use Cases
- Limitations

---

## What is the Encoding Process?

- The encoding process transforms binary data into a Base64 string.

  - How does the encoding process work?
    
    - Binary data is grouped into 24-bit chunks.
    - Each 24-bit chunk is split into four 6-bit segments.
    - Each 6-bit segment is mapped to a character in the Base64 character set.

---

## What is the Character Set?

- The character set is the collection of 64 characters used in Base64 encoding.
  
  - What characters are used?
    
    - Uppercase letters: A–Z
    - Lowercase letters: a–z
    - Digits: 0–9
    - Symbols: `+` and `/`

---

## What is Padding in Base64?

- Padding ensures that the encoded output has a length that is a multiple of 4 characters.

  - How is padding applied?
  
    - If the input data is not a multiple of 3 bytes, `=` characters are added to the end of the output.

---

## What are Use Cases of Base64 Encoding?

- Base64 is commonly used to encode binary data for transmission over text-based protocols.

  - Where is Base64 used?
  
    - Email (MIME)
    - Embedding images in HTML or CSS
    - Storing binary data in JSON or XML
    - Basic authentication in HTTP headers

---

## What are the Limitations of Base64 Encoding?

- Base64 increases the size of the data and is not suitable for large binary files.

  - What are specific limitations?
    
    - Encoded data is ~33% larger than the original
    - Not secure for encryption or obfuscation
    - Requires decoding before use in binary form
 
## Why is Base64 Encoding Used?

- Base64 encoding is used to safely transmit binary data over systems that are designed to handle text.

## Why can't binary data be transmitted directly?

- Many communication protocols (like HTTP, SMTP, or JSON) are designed to handle text, not raw binary.

  - What problems occur with raw binary?
    
    - Binary data may contain control characters that interfere with protocol parsing.
    - Some systems may corrupt or misinterpret binary data.
    - Binary data is not human-readable or easily logged/debugged.

---

## Why does Base64 solve this problem?

- Base64 converts binary data into a limited set of ASCII characters that are safe for transmission.
  
 - What characters does Base64 use?
  
    - A–Z, a–z, 0–9, `+`, `/`, and `=`

---

## Why is Base64 used in specific applications?

  - Why in Email (MIME)?
  
    - Email protocols like SMTP were originally designed for text, so Base64 allows attachments (images, documents) to be encoded safely.

  - Why in Web Development?
  
    - Base64 is used to embed images directly in HTML or CSS, avoiding external file requests.
  
  - Why in APIs and Authentication?
  
    - Base64 is used to encode credentials (e.g., in HTTP Basic Auth) and binary data in JSON payloads.

---

## Why is Base64 not used for encryption?

- Base64 is not a security mechanism—it only encodes data, not encrypts it.

  - What are the limitations?
  
    - It increases data size (~33% larger).
    - It does not protect data from being read or tampered with.

