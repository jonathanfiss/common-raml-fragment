# common-raml-fragment
<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!-- <a href="https://github.com/jonathanfiss/common-raml-fragment">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->

  <h3 align="center">Common Fragment RAML</h3>

  <p align="center">A template with reusable fragments to boost your projects!</p> 
</div>

<!-- ABOUT THE PROJECT -->
## About The Project

The **Common RAML Fragment** project aims to simplify the development of RAML (RESTful API Modeling Language) specifications by following predefined standards. It provides a set of reusable fragments that cover key aspects of RAML specifications, allowing you to create consistent and standardized specifications for your APIs.

## Project Contents

The project offers a variety of key resources to assist in the development of your RAML specifications:

### Resource Types

1. **System Layer**: This resource type is designed for the system layer and includes security measures such as `clientEnforcement`, as well as common headers shared across layers.
2. **Process Layer**: Intended for the processing layer, this resource type also includes `clientEnforcement` security measures and common headers across layers.
3. **Experience Layer**: For the experience layer, this resource type implements `oAuth2.0` security measures suitable for specific authentication scenarios.
4. **Generic**: This resource type provides a generic approach for other cases where none of the previous types directly apply.

### Standard Structures

- **Default Error Structure**: Defines the main error types that can be returned by the API using APIkit policies.
- **Common Headers Across Layers**: Includes headers that are shared across multiple layers of your API, ensuring consistency and compliance.
- **Query Parameters for Pagination and Sorting**: Defines common parameters used for pagination and sorting of results in your API calls.
- **Response Headers for Rate Limit Policies**: Defines response headers used in conjunction with rate-limiting policies.
- **Request Structures**: Includes request structures for common formats such as JSON, XML, and form-data.
- **Response Structures**: Defines response structures with HTTP status codes 200, 201, 202, and 204, for formats such as JSON and XML.

The **Common RAML Fragment** project streamlines the process of creating high-quality RAML specifications, saving time and ensuring compliance with established standards. Use these reusable resources to create more consistent and well-documented APIs.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage Instructions

1. Create a new RAML Fragment project in Design Centre named: "Common RAML Fragments"
2. Add all the contents of this repository into a ZIP excluding the license and readme.md file.
3. Go to your Design Centre Project and choose "Import", then select the ZIP.
4. Ensure you set the root RAML as the one which has been imported.
5. Publish this asset to Exchange.
7. This asset can now be imported into any new API Specification Design Centre project.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Used as the basis for creating this template.

* [Getting Started With RAML 1.0](https://medium.com/@shiv.jalli_26300/getting-started-with-raml-1-0-406377f8c1ab)
* [3 types of API fragments design strategies](https://blogs.mulesoft.com/api-integration/patterns/api-fragments-design-strategies/)
* [Eliminate Redundancies in RAML with Resource Types and Traits](https://www.baeldung.com/simple-raml-with-resource-types-and-traits)
* [RAML Version 1.0: RESTful API Modeling Language](https://github.com/raml-org/raml-spec/blob/master/versions/raml-10/raml-10.md/#resource-types-and-traits)


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/jonathanfiss/common-raml-fragment.svg?style=for-the-badge
[contributors-url]: https://github.com/jonathanfiss/common-raml-fragment/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jonathanfiss/common-raml-fragment.svg?style=for-the-badge
[forks-url]: https://github.com/jonathanfiss/common-raml-fragment/network/members
[stars-shield]: https://img.shields.io/github/stars/jonathanfiss/common-raml-fragment.svg?style=for-the-badge
[stars-url]: https://github.com/jonathanfiss/common-raml-fragment/stargazers
[issues-shield]: https://img.shields.io/github/issues/jonathanfiss/common-raml-fragment.svg?style=for-the-badge
[issues-url]: https://github.com/jonathanfiss/common-raml-fragment/issues
[license-shield]: https://img.shields.io/github/license/jonathanfiss/common-raml-fragment.svg?style=for-the-badge
[license-url]: https://github.com/jonathanfiss/common-raml-fragment/blob/master/LICENSE.txt

