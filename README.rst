AskSO - StackOverflow Python Question Assistant
-----------------------------------------------

This is a tool to help you construct a good question about Python on
`StackOverflow <http://stackoverflow.com/>`__, although it can help with
other forums too. It assumes that you've written some code that isn't
behaving correctly. This should not be a problem, as StackOverflow
generally expects you to show that you've tried something.

To install: run ``pip install ask-so`` in a terminal. You will need
``pip``, which you can install with the instructions
`here <https://pip.pypa.io/en/stable/installing/>`__.

To use:

1. (Optional, best if your question involves files) Navigate to the
   location of your code in a terminal.
2. Run ``askso`` in the terminal. If that doesn't work:
   ``python -m askso``. This will start a server.
3. Visit http://localhost:5000/ in your browser.
