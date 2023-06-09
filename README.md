# PresentationGPT
## Investor Deck Generator using ChatGPT and VBA
This code base enables users to generate an Investor Deck for a startup using ChatGPT and VBA (Visual Basic for Applications). The Investor Deck is a Powerpoint presentation that provides key information about the startup to potential investors. With this tool, users can easily create a professional-looking presentation by leveraging the power of ChatGPT and automating the process through VBA code.

### How it Works
1. #### Input Prompt: 
The user provides specific information to generate the Investor Deck. The prompt includes the following textfields:

* ##### Presentation Topic: 
The user specifies the topic of the Investor Deck, such as "Science". This ensures that the generated slides focus on the desired topic.

* ##### Website URL: 
The user provides the URL of the startup's website. This allows ChatGPT to gather information from the website and generate relevant content for the slides.

* ##### Template URL (Optional): 
If desired, the user can provide a URL to a presentation template. This template can be used to give the generated Investor Deck a consistent visual style and layout.

2. #### ChatGPT Integration: 
The code base integrates with the ChatGPT language model, powered by OpenAI's advanced natural language processing capabilities. It uses the generated text to populate the slides with relevant and informative content, based on the provided website URL.

3. #### VBA Automation: 
VBA code is utilized to automate the process of creating and formatting the Powerpoint slides. The VBA code interacts with the Powerpoint application, dynamically generating slides based on the information generated by ChatGPT.

### Features and Benefits
* #### Efficiency: 
By automating the Investor Deck generation process, this code base saves significant time and effort for users. They can quickly create high-quality presentations without manual content creation.
* #### Customization: 
The generated Investor Deck is tailored to the specific topic provided by the user. Each slide contains unique and relevant information based on the startup's website content.
* #### Professional Presentation: 
The VBA code ensures that the slides are formatted professionally, with consistent styling and layout. If a template URL is provided, the generated content will be applied to the template, resulting in a visually appealing and polished presentation.
* #### Adaptability: 
Users can easily modify the code base to incorporate additional features, such as including images, charts, or other visual aids, to enhance the Investor Deck further.

### Requirements
To use this code base, you need the following:
- Microsoft Office suite, including Powerpoint, with VBA enabled.
- ChatGPT API access to generate informative content based on the startup's website information.
### Instructions for Usage
- Open the VBA editor in Powerpoint.
- Import the provided VBA code from this code base.
- Ensure the ChatGPT API access is set up correctly and the necessary credentials are entered in the VBA code.
- Adjust any parameters or settings in the VBA code as needed, such as API configurations, slide layout, or additional styling.
- Run the VBA code to generate the Investor Deck slides based on the provided topic, startup's website content, and optional template URL.
### Limitations
- The quality and accuracy of the generated content depend on the capabilities and training of the ChatGPT language model.
- Customization options for slide design and content generation are limited to what is implemented in the VBA code.
- Users should review and refine the generated content as necessary to ensure accuracy and alignment with their specific startup's website information.
### Example
Here is an example of how to use this code base:

Input Prompt:

- Presentation Topic: Science
- Website URL: https://www.startup_page.com
- Template URL (Optional): https://www.template_slide.com

### ToDo


1. [ ] Generate VBA for Sales Deck
    - [ ] Create VBA code that generates a sales deck using a single-page HTML input.
    - [ ] Implement logic to extract relevant information from the HTML and populate the slides with sales-related content.
2.  [ ] Generate VBA for Investor Deck
    - [ ] Develop VBA code that generates an investor deck presentation using a single-page HTML input.
    - [ ] Extract key details from the HTML and utilize them to populate the slides with investor-focused content.
3. [ ] Generate VBA for Marketing Deck
    - [ ] Design VBA code to generate a marketing deck presentation using a single-page HTML input.
    - [ ] Extract relevant marketing information from the HTML and populate the slides with engaging content.
    - [ ] Implement styling and visual elements to create an impactful marketing presentation.
4. [ ] Generate Presentation without Background
    - [ ] Create VBA code to generate a presentation without a background using a single-page HTML input.
    - [ ] Extract content from the HTML and generate slides with clear formatting and layout.
    - [ ] Ensure the generated presentation has a clean and minimalistic look.
5. [ ] Generate Presentation with Background
    - [ ] Develop VBA code to generate a presentation with a background using a single-page HTML input.
    - [ ] Extract content from the HTML and apply it to slides with an appealing background design.
6. [ ] Generate Presentation with Background based on Template Presentation
    - [ ] Enhance the existing VBA code to generate a presentation with a background based on a template presentation.
    - [ ] Extract content from the HTML and apply it to the template slides while preserving the background design.
    - [ ] Ensure the generated presentation maintains consistency with the template's visual theme.
7. [ ] Generate Presentation with Background using the Whole Page
    - [ ] Extend the VBA code to generate a presentation with a background using the whole page of the HTML input.
    - [ ] Extract content from the entire HTML page and generate slides with background design and appropriate content placement.
    - [ ] Implement styling and formatting to create an immersive presentation experience.
8. [ ] Generate Presentation with Background based on Template Presentation using the Whole Page
    - [ ] Further enhance the existing VBA code to generate a presentation with a background based on a template presentation, using the whole website as an input.
    - [ ] Extract content from the entire website and apply it to the template slides while preserving the background design.
    - [ ] Ensure the generated presentation maintains consistency with the template's visual theme and utilizes the complete page content.


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)