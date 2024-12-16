# Konwinski Prize Solution

This project is an attempt at the Konwinski Prize challenge - creating an AI system capable of resolving GitHub issues automatically.

## Setup

1. Clone the repository:
```bash
git clone https://github.com/dakowa/konwinski-prize-solution.git
cd konwinski-prize-solution
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Project Structure

- `src/`: Main source code
  - `issue_processor.py`: Core logic for processing GitHub issues
  - `models.py`: Model definitions and training code
- `tests/`: Unit tests
- `data/`: Data storage (git-ignored)
- `models/`: Trained models storage (git-ignored)

## Development Roadmap

1. Setup basic infrastructure (✓)
2. Implement issue processing pipeline
3. Develop code generation system
4. Test and iterate on real GitHub issues
5. Optimize for SWE-bench metrics

## Next Steps

1. Set up your development environment following the setup instructions above
2. Review the code structure in src/
3. Run the tests to ensure everything is working
4. Start with implementing basic issue analysis

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT