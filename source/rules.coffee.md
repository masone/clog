Rules for how each token type is weighted in terms of maintainability.

    module.exports =
      "+": 1
      "=": 1
      "(": 1
      ",": 1
      "-": 1
      ":": 1

      ".": 2
      "[": 2
      "{": 2

      "?": 3
      "->": 3
      "++": 3

      "--": 4

      "@": 5
      "?.": 5

      "=>": 6

      "BOOL": 1
      "CALL_END": 0
      "CALL_START": 2
      "CLASS": 30
      "COMPARE": 1
      "COMPOUND_ASSIGN": 2
      "ELSE": 2
      "EXTENDS": 15
      "FOR": 10
      "FORIN": 10
      "FOROF": 10
      "IDENTIFIER": 1
      "IF": 4
      "INDENT": 1
      "INDEX_START": 2
      "LEADING_WHEN": 1
      "LOGIC": 1
      "MATH": 1
      "NULL": 3
      "NUMBER": 1
      "PARAM_START": 3
      "REGEX": 10
      "RELATION": 3
      "RETURN": 0
      "SHIFT": 4
      "STRING": 1
      "SUPER": 7
      "SWITCH": 7
      "TERMINATOR": 1
      "UNARY": 3
      "UNARY_MATH": 1
