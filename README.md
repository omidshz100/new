# PhD Supervisor Selection Tool

A comprehensive web-based tool for managing and organizing potential PhD supervisors with advanced filtering, note-taking, and nationality detection capabilities.

## 🎯 Features

### Core Functionality
- **Smart Name List**: Display of 288+ researcher names with automatic nationality detection
- **PhD Selection System**: Select up to 10 potential supervisors with visual feedback
- **Advanced Notes**: Rich text notes with automatic URL link detection and conversion
- **Multi-Filter System**: Filter by notes, selection status, nationality, and search terms
- **Click-to-Copy**: One-click name copying to clipboard for easy application use

### Advanced Capabilities
- **Nationality Detection**: AI-powered detection of researcher origins with flag indicators
- **Persistent Storage**: All notes and selections saved in browser local storage
- **Real-time Updates**: Instant filtering and selection updates without page refresh
- **Top Recommendations**: Pre-marked top-tier supervisors for quick identification
- **Country Statistics**: Live breakdown of researcher distribution by nationality

### Technical Features
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Performance Optimized**: Fast checkbox responses and smooth interactions
- **Browser Compatible**: Works with modern browsers (Chrome, Firefox, Safari, Edge)
- **No Dependencies**: Pure HTML, CSS, and JavaScript - no external libraries required

## 🚀 Quick Start

1. **Open the Tool**: Load `main.html` in any modern web browser
2. **Browse Names**: Scroll through the list of researchers with nationality flags
3. **Select Candidates**: Check up to 10 PhD supervisor candidates
4. **Add Notes**: Click "Add Note" to save research information and links
5. **Filter & Search**: Use dropdowns and search to find specific researchers
6. **Copy Names**: Click on any name to copy it to clipboard for applications

## 📋 Usage Guide

### Selecting PhD Supervisors
- Check the "PhD Candidate" box next to promising supervisors
- Maximum of 10 selections enforced automatically
- View selected list with the "View Selected List" button
- Yellow highlighting indicates selected candidates

### Managing Notes
- **Add URLs**: Paste LinkedIn profiles, university pages, research links
- **Auto-linking**: URLs automatically become clickable after saving
- **Rich Display**: Toggle between edit and view modes
- **Persistent Storage**: Notes saved automatically in browser

### Filtering Options
- **All Names**: View complete list (288+ researchers)
- **Names with Notes**: Show only researchers you've researched
- **Names without Notes**: Find researchers needing investigation
- **Selected PhD Candidates**: Focus on your chosen supervisors
- **Country Filter**: Filter by nationality (German, Italian, French, etc.)

### Country-Specific Features
- **🇩🇪 German**: Largest group, excellent PhD programs (Max Planck, TU Munich)
- **🇬🇧 British**: Alternative PhD structure, English-speaking
- **🇸🇪 Scandinavian**: Strong research funding, work-life balance
- **And 16+ other nationalities**: Comprehensive global coverage

## 🛠️ Technical Implementation

### Architecture
- **Frontend-Only**: No server required, runs entirely in browser
- **Local Storage**: Uses browser localStorage for data persistence
- **Event-Driven**: Efficient DOM manipulation with event delegation
- **Modular Design**: Organized functions for easy maintenance

### Key Technologies
- **HTML5**: Semantic markup and modern form elements
- **CSS3**: Flexbox layouts, transitions, and responsive design
- **ES6+ JavaScript**: Modern JavaScript with async/await and classes
- **Clipboard API**: Modern clipboard access with fallback support

### Performance Features
- **Optimized Rendering**: Selective DOM updates instead of full rebuilds
- **Efficient Filtering**: Smart algorithms for real-time search and filtering
- **Memory Management**: Proper cleanup and garbage collection
- **Fast Interactions**: Sub-100ms response times for all user actions

## 📊 Data Overview

### Researcher Coverage
- **Total Names**: 288+ researchers
- **Top Countries**: German (largest), Italian, French, British, Chinese
- **Research Areas**: Machine Learning, Computer Vision, AI, Data Science
- **Institution Types**: Universities, Max Planck Institutes, Research Centers

### Quality Assurance
- **Curated List**: Hand-selected top researchers in AI/ML fields
- **Nationality Accuracy**: Advanced pattern matching for origin detection
- **Institution Verification**: Focus on reputable academic institutions
- **PhD Relevance**: All researchers actively supervise PhD students

## 🔧 Customization

### Adding New Researchers
1. Add names to the `names` array in `main.html`
2. Update nationality patterns if needed in `guessNationality()`
3. Add to recommended list if they're top-tier supervisors

### Modifying Nationality Detection
- Edit patterns in the `guessNationality()` function
- Add new countries to the dropdown filter
- Update flag emojis and country names

### Styling Customization
- Modify CSS variables for color schemes
- Adjust responsive breakpoints
- Customize animation timings and effects

## 📱 Browser Support

### Fully Supported
- **Chrome**: 70+
- **Firefox**: 65+
- **Safari**: 12+
- **Edge**: 79+

### Limited Support
- **IE11**: Basic functionality only (no clipboard API)
- **Mobile Browsers**: iOS Safari 12+, Chrome Mobile 70+

## 🤝 Contributing

We welcome contributions to improve the PhD Supervisor Selection Tool!

### How to Contribute
1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Contribution Areas
- **New Features**: Additional filtering options, export capabilities
- **Performance**: Optimization improvements, faster rendering
- **Accessibility**: Screen reader support, keyboard navigation
- **Mobile**: Touch interactions, responsive improvements
- **Data**: New researcher additions, nationality improvements

### Code Style
- Use modern ES6+ JavaScript
- Follow semantic HTML practices
- Maintain CSS organization and naming conventions
- Include comments for complex logic
- Test across multiple browsers

## 📄 License

### MIT License

```
Copyright (c) 2025 PhD Supervisor Selection Tool Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### Open Source Notice

This project is **open source** and free to use, modify, and distribute under the MIT License. We believe in the power of open collaboration to help students worldwide find amazing PhD opportunities.

#### What this means:
- ✅ **Free to use** for personal and commercial purposes
- ✅ **Free to modify** and customize for your needs
- ✅ **Free to distribute** and share with others
- ✅ **Free to contribute** improvements back to the community

#### Attribution
While not required, we appreciate attribution when you use or modify this tool:
```
"Built with PhD Supervisor Selection Tool (https://github.com/your-repo)"
```

## 🎓 For Students

This tool was created to help students navigate the complex world of PhD applications. We understand that finding the right supervisor is crucial for your academic success and career development.

### Tips for Success
1. **Research Thoroughly**: Use the notes feature to track each supervisor's work
2. **Diversify Your List**: Select supervisors from different countries and institutions
3. **Quality over Quantity**: Better to have 5 well-researched applications than 10 generic ones
4. **Use the Links**: Click through to LinkedIn profiles and university pages
5. **Keep Notes Updated**: Track email responses and application deadlines

### Best Practices
- **Start Early**: PhD applications take months of preparation
- **Personal Connections**: Look for ways to connect with potential supervisors
- **Research Fit**: Ensure your interests align with their current work
- **Funding Awareness**: Check funding availability in different countries
- **Application Requirements**: Note different requirements for each country/institution

## 📞 Support & Community

### Getting Help
- **Issues**: Report bugs and request features via GitHub Issues
- **Discussions**: Join community discussions about PhD applications
- **Documentation**: Check this README for comprehensive guidance
- **Examples**: See the tool in action with sample data

### Community Guidelines
- Be respectful and supportive of fellow PhD applicants
- Share knowledge and experiences constructively
- Contribute improvements that benefit everyone
- Maintain the academic integrity of the research community

## 🔮 Future Roadmap

### Planned Features
- **Export Functionality**: PDF/Excel export of selected supervisors
- **Email Templates**: Pre-built templates for supervisor outreach
- **Deadline Tracking**: Application deadline management
- **Institution Details**: University rankings and program information
- **Collaboration Features**: Share lists with advisors and peers

### Long-term Vision
- **Mobile App**: Native iOS and Android applications
- **API Integration**: Connect with university databases
- **AI Recommendations**: Smart matching based on research interests
- **Global Expansion**: Include researchers from more countries and fields
- **Community Features**: User reviews and application success stories

---

## 📊 Statistics

- **Total Researchers**: 288+
- **Countries Covered**: 19+
- **Institution Types**: Universities, Research Institutes, Labs
- **Research Fields**: AI, ML, Computer Vision, Data Science, and more
- **Active Development**: Regular updates and improvements

---

**Made with ❤️ for the global PhD student community**

*Happy PhD hunting! 🎓✨*