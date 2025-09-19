# POEPart1

   public boolean checkCellPhoneNumber(String cellNumber) {
        Pattern pattern = Pattern.compile("^\\+27\\d{9,10}$");
        Matcher matcher = pattern.matcher(cellNumber);
        return matcher.matches();
    }


This project utilized the Gemini large language model developed by Google to generate parts of the codebase.
