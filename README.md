# ShoppingCart

# SQL Configuration
## Create Database first
```
CREATE DATABASE shopping;
```

## Table structure for table `tbl_product`
```
CREATE TABLE IF NOT EXISTS `tbl_product` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `name` varchar(255) NOT NULL,
  `image` varchar(255) NOT NULL,
  `price` double(10,2) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=MyISAM  DEFAULT CHARSET=latin1 AUTO_INCREMENT=10 ;
```

## prepopulate data for table `tbl_product`
```
INSERT INTO `tbl_product` (`id`, `name`, `image`, `price`) VALUES
(1, 'Abyssinian', 'Abyssinian.jpg', 100.00),
(2, 'American Shorthair', 'American Shorthair.jpg', 150.00),
(3, 'Brazilian Shorthair', 'Brazilian Shorthair.jpg', 200.00),
(4, 'Chartreux', 'Chartreux.jpg', 400.00),
(5, 'Maine Coon', 'mainecoon.jpg', 980.00),
(6, 'Persian', 'Persian.jpg', 100.00),
(7, 'Scottish Fold', 'Scottish Fold.jpg', 500.00),
(8, 'Somali', 'somali.jpg', 340.00);
```