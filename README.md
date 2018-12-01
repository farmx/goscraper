# goscraper
[Golang](http://golang.org/) package to quickly return the webpage title

## Usage
    func main() {
		s, err := goscraper.Scrape("https://www.w3.org/", 5)
		if err != nil {
			fmt.Println(err)
			return
		}
		fmt.Printf("Title : %s\n", s.Preview.Title)
	}

output: 

**Title :** World Wide Web Consortium (W3C)  

## License

Goscraper is licensed under the [MIT License](./LICENSE).
