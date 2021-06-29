
# Glorified Studios Coding Conventions

## Lua

The following are a set of guidelines for programming Lua-related content for Glorified Studios:

- Indentation should be 4 wide spaces.
- Variables are to be formatted as follows:
  - GlobalVars *(including keys of tables, example Table.Key)*
  - localVars
  - CONFIG_VARS
  - Enum.ENUM_VALUE
- Every bracket with the exception of square brackets should be spaced.
- Every file should begin with an empty line.
- Always use default Lua operators if others are provided. For example, always use `or` instead of `||`.
- If statements should not contain brackets unless it; is a large statement, has mathematical equations or if needed for ease of reading.
- String identifiers, such as for events (or hooks in Garry's Mod), should be formatted like `Library.FileName.EventName`.
