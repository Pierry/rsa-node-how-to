RSA Node - How to
==

1. Motivation
2. Converter
3. Libraries
4. Example

Motivation
==

Converter
==

Libraries
==

Example
==

      encrypt (secret: string): string {
		    const publicKey: string = '-----BEGIN PUBLIC KEY-----YOUR KEY-----END PUBLIC KEY-----'
		    const key = new NodeRSA(publicKey)
		    const message = Buffer.from(secret)
		    const encrypted = key.encrypt(message, 'base64', 'utf8')
		    return encrypted.toString()
	    }


https://the-x.cn/en-US/certificate/XmlToPem.aspx
