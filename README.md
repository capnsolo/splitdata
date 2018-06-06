# splitdata
An ugly script for splitting a labeled dataset into training and test sets.

## Usage
1. Make sure your data is formatted correctly.

```
data/
- label1/
-- image1.png
-- image2.png
- label2/
-- image3.png
-- image4.png
```

2. Run the script
```
cd data
splitdata
```

## Known issues/limitations
I might fix these if it comes up but it works for now.
- only works for `.png` files
- split is hardcoded 80/20

## Contributing
PRs welcome.
