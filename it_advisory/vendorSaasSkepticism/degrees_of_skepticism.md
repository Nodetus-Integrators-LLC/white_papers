
# APPENDIX A.2: Degrees of Skepticism Summary

The formula represents a mathematical way of calculating the degree of skepticism—
where skepticism increases with greater layers of separation from the root and also the
number of layers shared by a development team (that does not directly represent the
business owner’s intention). The diagram is to showcase the different layers of product
development, distribution, usage, and the degree of skepticism a business owner should
exercise. The further the business owner is from having direct hands-on access to the
products codebase, configuration base, etc., the greater the degree of skepticism that
should be applied when reviewing or using a product.

## Cloud Elements

As you see in the diagram in the orange outlined “cloud,” the instances represent
different stages in the product development and release lifecycle. "Dev" stands for the
development environment, "Test" is for testing the product, and "Prod" signifies the
production environment. When you move toward the user, we eventually get to the
Production environment which serves the user community.

## Degrees (removed) from “Root” (x=1) Product

Within each tier, we use powers to indicate how many degrees separated the product
becomes as it moves towards the user in this process. We start with the source code,
product development team, and the administration of that code. At X to the zero power,
we are at 1… as we move toward the instance of the product (a cloud version instance
of it provided to a user and the configure that product (another variable, configuration
issues), etc. We get toward 4 degrees of separation for each level.

| Exponent Degree (Separation) | Level of Product           | Summary |
|------------------------------|----------------------------|---------|
| X^0 (0)                      | Product A                  | Representative of the root product, original codebase |
| X^1                          | Product A Instance         | An instance or iteration of Product A |
| X^2                          | Configured Product A Instance | A custom configuration of the Product A Instance |
| X^2 + n                      | Tested Configured Product A Instance | The tested and QA’d version of the configured product. Note: Skepticism increases depending on testing layers or processes |
| X^3                          | Admin Facing Product       | A version tailored of the product for administrators |
| X^4                          | User Facing Product        | A version of the product tailored for end-users. The degrees symbolize the depth and variation of the product from its original form. |

## SaaS Black Boxes

Indicated in the color of the boxes themselves, at the root, we usually encounter a black
box at the source code and the user, which is a rendered service provided. These
parameters are mapped to:

- **Obfuscation**: Indicates areas where there might be hidden processes or
concealed data. These are areas that require heightened scrutiny because
concealed or obfuscated data can be a potential point of vulnerability or
misrepresentation. Depending on the product’s intent, this can mean many
things, especially Federally, when seeking how connected certain environments
and what ports are being routed, information is being shared, what is physically
being transmitted in and outside the boundaries.

- **Color Gradient**: By visually representing the stages of a product from a "black
box" to a more transparent stage, the graphic expresses the increasing need for
scrutiny and skepticism. The more "black box" a process or product is, the more
rigorous and skeptical one should be, as it's harder to verify its integrity or
understand its inner workings (as discussed in Obfuscation).

In the broader context of product development and procurement, especially in sensitive
industries or sectors, such nuances play a significant role. Transparency ensures
accountability, while obscurity can lead to potential risks. This is especially crucial for
stakeholders like the NIH, in terms of Contracts and Procurement, to ensure the
products or services you're procuring meet the necessary standards of transparency and
integrity.
