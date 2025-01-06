# [TakeMeTo](https://dogo6647.github.io/takemeto)
A simple website with the only purpose of taking you to any URL you desire, in a redirect, in an iframe, or in a new tab. Partially written with ChatGPT because I'm too lazy and don't want to spend too much time on this. Can be useful if you want a minimal new tab page [(For a more feature-rich new tab page, see Gnutab)](https://github.com/Dogo6647/gnutab) or for "escaping" embedded web browsers such as those in gaming consoles or login popups (provided you can access GitHub to visit this page first).
<br><br>
## What does it do?
It takes you to a URL. It's that simple. A uniform resource locator (URL), colloquially known as an address on the Web,[1] is a reference to a resource that specifies its location on a computer network and a mechanism for retrieving it. A URL is a specific type of Uniform Resource Identifier (URI),[2][3] although many people use the two terms interchangeably.[4][a] URLs occur most commonly to reference web pages (HTTP/HTTPS) but are also used for file transfer (FTP), email (mailto), database access (JDBC), and many other applications.

Most web browsers display the URL of a web page above the page in an address bar. A typical URL could have the form http://www.example.com/index.html, which indicates a protocol (http), a hostname (www.example.com), and a file name (index.html).
History

Uniform Resource Locators were defined in RFC 1738 in 1994 by Tim Berners-Lee, the inventor of the World Wide Web, and the URI working group of the Internet Engineering Task Force (IETF),[7] as an outcome of collaboration started at the IETF Living Documents birds of a feather session in 1992.[7][8]

The format combines the pre-existing system of domain names (created in 1985) with file path syntax, where slashes are used to separate directory and filenames. Conventions already existed where server names could be prefixed to complete file paths, preceded by a double slash (//).[9]

Berners-Lee later expressed regret at the use of dots to separate the parts of the domain name within URIs, wishing he had used slashes throughout,[9] and also said that, given the colon following the first component of a URI, the two slashes before the domain name were unnecessary.[10]

Early WorldWideWeb collaborators including Berners-Lee originally proposed the use of UDIs: Universal Document Identifiers. An early (1993) draft of the HTML Specification[11] referred to "Universal" Resource Locators. This was dropped some time between June 1994 (RFC 1630) and October 1994 (draft-ietf-uri-url-08.txt).[12] In his book Weaving the Web, Berners-Lee emphasizes his preference for the original inclusion of "universal" in the expansion rather than the word "uniform", to which it was later changed, and he gives a brief account of the contention that led to the change.
Syntax
Main article: Uniform Resource Identifier § Syntax

Every HTTP URL conforms to the syntax of a generic URI. The URI generic syntax consists of five components organized hierarchically in order of decreasing significance from left to right:[13]: §3 

URI = scheme ":" ["//" authority] path ["?" query] ["#" fragment]

A component is undefined if it has an associated delimiter and the delimiter does not appear in the URI; the scheme and path components are always defined.[13]: §5.2.1  A component is empty if it has no characters; the scheme component is always non-empty.[13]

Internet users are distributed throughout the world using a wide variety of languages and alphabets, and expect to be able to create URLs in their own local alphabets. An Internationalized Resource Identifier (IRI) is a form of URL that includes Unicode characters. All modern browsers support IRIs. The parts of the URL requiring special treatment for different alphabets are the domain name and path.[18][19]

The domain name in the IRI is known as an Internationalized Domain Name (IDN). Web and Internet software automatically convert the domain name into punycode usable by the Domain Name System; for example, the Chinese URL http://例子.卷筒纸 becomes http://xn--fsqu00a.xn--3lr804guic/. The xn-- indicates that the character was not originally ASCII.[20]

The URL path name can also be specified by the user in the local writing system. If not already encoded, it is converted to UTF-8, and any characters not part of the basic URL character set are escaped as hexadecimal using percent-encoding; for example, the Japanese URL http://example.com/引き割り.html becomes http://example.com/%E5%BC%95%E3%81%8D%E5%89%B2%E3%82%8A.html. The target computer decodes the address and displays the page.[18] 

Protocol-relative links (PRL), also known as protocol-relative URLs (PRURL), are URLs that have no protocol specified. For example, //example.com will use the protocol of the current page, typically HTTP or HTTPS.[21][22]

***Does that answer your question?***
