# MIME

## What is MIME?

- MIME (Multipurpose Internet Mail Extensions) is a standard that extends the format of email messages to support text in character sets other than ASCII, as well as attachments like images, audio, video, and application files.

  - What are the key components of MIME?
  
    - MIME Headers
    - MIME Types
    - MIME Encoding
    - MIME Multipart Messages

---

## What are MIME Headers?

- MIME headers are additional fields in an email that describe the content type and encoding of the message body.

  - What are common MIME headers?
  
    - `Content-Type`
    - `Content-Disposition`
    - `Content-Transfer-Encoding`

  #### What is Content-Type?
  
    - Specifies the media type of the content (e.g., `text/plain`, `image/jpeg`, `application/pdf`).
  
  #### What is Content-Disposition?
  
    - Indicates how the content should be displayed (e.g., inline or as an attachment).
  
  #### What is Content-Transfer-Encoding?
  
   - Specifies the encoding used to safely transmit the content (e.g., `base64`, `quoted-printable`).

---

## What are MIME Types?

  - MIME types define the nature and format of a file or data.

  - What are examples of MIME types?
  
    - `text/plain` – plain text
    - `text/html` – HTML content
    - `image/png` – PNG image
    - `application/json` – JSON data
    - `audio/mpeg` – MP3 audio

---

## What is MIME Encoding?

- MIME encoding allows binary or non-ASCII data to be transmitted over text-based protocols like SMTP.

  - What are common MIME encodings?
  
    - `Base64` – encodes binary data into ASCII
    - `Quoted-Printable` – encodes mostly ASCII text with special characters

---

## What are MIME Multipart Messages?

- Multipart messages allow multiple pieces of content (e.g., text and attachments) to be included in a single email.

  - What are common multipart types?
  
    - `multipart/mixed` – for emails with attachments
    - `multipart/alternative` – for emails with both plain text and HTML versions
    - `multipart/related` – for emails with embedded media (e.g., images in HTML)
    
  - What is a boundary in multipart messages?
  
    - A boundary is a unique string used to separate different parts of a multipart message.

---

## What are the uses of MIME?

  - Sending attachments in email
  - Supporting international character sets
  - Embedding images and media in HTML emails
  - Defining content types in HTTP headers

