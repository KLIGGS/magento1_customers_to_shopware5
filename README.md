# Magento 1 API Script export customers
Export of Magento 1 customers as XML file for importing to Shopware 5

## INTRODUCTION

Shopware uses bcrypt hash algorithm. User passwords only work if hash algorithm is md5 and
comparison at Shopware 5 is equal to Magento 1

As md5 hash is a one-way function you cannot revert to plain text password.

## REQUIREMENTS

- Magento 1.x
- Shopware 5

## INSTALLATION

1. Place this script in Magento root
2. Alter credentials
3. Check realtive path to Magento API
4. Adjust filters

Try first with a small default data set if import works in general

## TROUBLESHOOTING

Possible reasons why import to Shopware 5 fails.

- xml syntax
- missing mandatory input
- input not matching Shopware requirements
- passwords fail -> adjust in Shopware 5 to md5




